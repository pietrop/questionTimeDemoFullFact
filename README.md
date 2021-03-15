## Brief of the project

<!-- _One liner + link to confluence page_
_Screenshot of UI - optional_ -->

Demo POC of adding interactive video quotes ([quickQuote](https://pietropassarelli.com/quickQuote.html)) to Full Fact Question time fact checking - January 22, 2016

- [before - static quotes](http://pietropassarelli.com/questionTimeDemoFullFact/static_quotes.html)
- [after - interactive quotes](http://pietropassarelli.com/questionTimeDemoFullFact/interactive_quotes.html)

## Setup

<!-- _stack - optional_
_How to build and run the code/app_ -->

```
git clone git@github.com:pietrop/questionTimeDemoFullFact.git
```

```
cd questionTimeDemoFullFact
```

## Usage

see `/static_quotes.html` and `interactive_quotes.html`

The interactive quotes parts where originally generated using [quickQuote](https://pietropassarelli.com/quickQuote/)

## System Architecture

Just an HTML demo

<!-- _High level overview of system architecture_ -->

<!-- ## Documentation

There's a [docs](./docs) folder in this repository.

[docs/notes](./docs/notes) contains dev draft notes on various aspects of the project. This would generally be converted either into ADRs or guides when ready.

[docs/adr](./docs/adr) contains [Architecture Decision Record](https://github.com/joelparkerhenderson/architecture_decision_record).

> An architectural decision record (ADR) is a document that captures an important architectural decision made along with its context and consequences.

We are using [this template for ADR](https://gist.github.com/iaincollins/92923cc2c309c2751aea6f1b34b31d95) -->

## Development env

Not using node/npm

 <!-- _How to run the development environment_ -->

<!-- - npm > `6.1.0`
- [Node 12](https://nodejs.org/docs/latest-v12.x/api/)

Node version is set in node version manager [`.nvmrc`](https://github.com/creationix/nvm#nvmrc)

```
nvm use
```
-->

<!-- _Coding style convention ref optional, eg which linter to use_ -->

<!-- _Linting, github pre-push hook - optional_ -->

Using git lfs for large media

- [An open source Git extension for versioning large files](https://git-lfs.github.com/)
- [Configuring Git Large File Storage
  ](https://docs.github.com/en/github/managing-large-files/configuring-git-large-file-storage)

```
git lfs track *.mp3
git lfs track *.mp4
```

## Build

<!-- _How to run build_ -->

_NA_

## Tests

<!-- _How to carry out tests_ -->

_NA_

## Deployment

<!-- _How to deploy the code/app into test/staging/production_ -->

Onto github pages, in root of project, via github repo settigns page.
