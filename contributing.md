# Contributing

> This project has a [code of conduct][coc].
> By interacting with this repository, organization, or community you agree to
> abide by its terms.

Hi!
👋
We’re excited that you’re interested in contributing!
Take a moment to read the following guidelines.
And thanks for contributing to **unist** (**syntax-tree**)!
👏👌✨

If you’re raising an issue, please understand that people involved with this
project often do so for fun, next to their day job; you are not entitled to
free customer service.

## Contents

* [Ecosystem](#ecosystem)
* [Contributions](#contributions)
  * [Financial support](#financial-support)
  * [Improve documentation](#improve-documentation)
  * [Improve issues](#improve-issues)
  * [Give feedback on issues](#give-feedback-on-issues)
  * [Write code](#write-code)
* [Support](#support)
* [Submitting an issue](#submitting-an-issue)
* [Submitting a pull request](#submitting-a-pull-request)
* [Resources](#resources)
* [License](#license)

## Ecosystem

The collective ([unified][]) consists of several organizations and separate
projects: most of them are tiny, and many of them have a utility
([`mdast-util-to-hast`][mdast-util-to-hast]), a plugin
([`remark-rehype`][remark-rehype]), and relate to an ecosystem
([`remark`][remark]) and a syntax tree ([mdast][]).
Try and pick the right place to contribute to so we can help you faster.

## Contributions

There’s several ways to contribute, not just by writing code.

### Financial support

It’s possible to support us financially by becoming a backer or sponsor through
[Open Collective][collective].
With this support, we can pay for project leadership, finance non-coding work,
or to do fun things for the community like getting stickers for contributors.
You’ll be helping unified’s maintainers manage and improve existing projects,
and additionally support our work to develop new and exciting projects, such
as [micromark][].

### Improve documentation

As a user of this project you’re perfect for helping us improve our docs.
Typo corrections, error fixes, better explanations, new examples, etcetera.
Anything!

### Improve issues

Some issues lack information, aren’t reproducible, or are just incorrect.
Help make them easier to resolve.

### Give feedback on issues

We’re always looking for more opinions on discussions in the issue tracker.

### Write code

Code contributions are very welcome.
It’s often good to first create an issue to report a bug or suggest a new
feature before creating a pull request to prevent you from doing unnecessary
work.

## Support

See [`support.md`][support] on how to get help.

## Submitting an issue

* The issue tracker is for issues.
  See [`support.md`][support] on how to get help.
* Search the issue tracker (including closed issues) before opening a new
  issue
* Ensure you’re using the latest version of projects
* Use a clear and descriptive title
* Include as much information as possible: steps to reproduce the issue,
  error message, version, operating system, etcetera
* The more time you put into an issue, the more we will
* The best issue report is a [failing test][unit-test] proving it

## Submitting a pull request

* Non-trivial changes are often best discussed in an issue first, to prevent
  you from doing unnecessary work
* For ambitious tasks, you should try to get your work in front of the
  community for feedback as soon as possible
* New features should be accompanied with tests and documentation
* Don’t include unrelated changes
* Lint and test before submitting code by running `$ npm test`
* Write a convincing description of why we should land your pull request:
  it’s your job to convince us

## Resources

* [How to contribute to open source](https://opensource.guide/how-to-contribute/)
* [Making your first contribution](https://medium.com/@vadimdemedes/making-your-first-contribution-de6576ddb190)
* [Using pull requests](https://help.github.com/articles/about-pull-requests/)
* [GitHub help](https://help.github.com)

## License

This document has the following license:
[CC-BY-4.0][license] © [Titus Wormer][author]

<!-- Definitions -->

[license]: https://creativecommons.org/licenses/by/4.0/

[author]: http://wooorm.com

[coc]: https://github.com/syntax-tree/.github/blob/main/code-of-conduct.md

[mdast]: https://github.com/syntax-tree/mdast

[unified]: https://github.com/unifiedjs/unified

[remark]: https://github.com/remarkjs/remark

[mdast-util-to-hast]: https://github.com/syntax-tree/mdast-util-to-hast

[remark-rehype]: https://github.com/remarkjs/remark-rehype

[unit-test]: https://twitter.com/sindresorhus/status/579306280495357953

[collective]: https://opencollective.com/unified

[micromark]: https://github.com/micromark/micromark

[support]: support.md
