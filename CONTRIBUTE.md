# Contributing

To contribute, modify/add notes in Anki, then export via the [CrowdAnki plugin](https://ankiweb.net/shared/info/1788670778) and make a pull request.

Please feel free to fork and contribute to this repo I only ask that:

## Guidelines for Contributing

1. Please use MathJax when creating equations as they do not create images and render on the fly.
2. Please minimize the use of images if possible in order to keep the deck as accesslbe to those using screenreaders as possible.
3. When creating additional decks please use the following example naming schema when titling decks as this helps keep the deck organized into folders.

- GA Tech OMSCS::Computer Networks::Lesson 1: Intro, History, and Internet Arch.

4. When creating new cards use the guidelines outlined in from [20 Rules of Formulating Knowledge](http://super-memory.com/articles/20rules.htm) and [Anki Flashcard: 13 best practices](https://medschoolinsiders.com/medical-student/anki-flashcard-best-practices-how-to-create-good-cards/) especially the following:

    1. Stick to the minimum information principle
       - Simple items are easier to remember
       - Repetitions of simple items are easier to schedule
       - Simple items help with chunking in the brain.
       - Break up more complex cards into simpler ones
    2. Be concise
    3. Cloze deletion is easy and effective for larger amounts of information.
    4. Use mnemonic techniques.
    5. Attack the same queston from a different angle.
    6. Use Images, Photos, and Figures when not otherwise possible.

## Signing your commits

If you would like to sign your commits you can use the same SSH key to sign your commits as youdo for pushing to your repo:

[Creating a signing key using SSH and adding it to your Github Profile](https://docs.github.com/en/authentication/managing-commit-signature-verification/about-commit-signature-verification#ssh-commit-signature-verification)

After you are finished setting up signing you can ensure that all commits are signed automatically.

```bash
git config --global commit.gpgsign true
```
