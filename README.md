Javascript Speech Detection
======
 (**JavaScript**)-only


## Synopsis

Just a basic Javascript Speech Detection so there's not much to it.

## Code Example

```
recognition.addEventListener('result', e => {
    const transcript = Array.from(e.results)
      .map(result => result[0])
      .map(result => result.transcript)
      .join('');

      const poopScript = transcript.replace(/poop|poo|shit|dump/gi, '💩');
      p.textContent = poopScript;

      if (e.results[0].isFinal) {
        p = document.createElement('p');
        words.appendChild(p);
      }
```

## Motivation

Learning and enforcing good structural and practical **strategies** for JavaScript development.

### Directory Layout

```

│   └──style.css       # Basic CSS stylesheet
│   └── main.js          # Main app source
│── index.html           # Main entry point
└── README.md            # This file

```

## Usage

***

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

0.1.0 Finalized the example

## Tests

Basic non-automated manual browser test aka no test :P

## Contributors

Standing on the shoulders of all the giants before me.

## Contact
#### sorcererizza
* E-mail: izzaannsamax@gmail.com

