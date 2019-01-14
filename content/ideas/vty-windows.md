---
title: Add windows support to vty
---

[`vty`](https://hackage.haskell.org/package/vty) is a high-level ncurses alternative written in Haskell. It provides
a high-level interface for interacting with the terminal in an abstract manner.
Currently `vty` only works on unix platforms so libraries which depend on `vty`
also don't work on windows.

The primary motivation for this project is to make it possible to use applications
written in [`brick`](https://hackage.haskell.org/package/brick) on windows.

The project is labelled as advanced as it isn't clear what precisely is necessary
to implement this feature. A proposal should include significant enough detail
to show that the student has researched the implementation and has a good idea
about how to complete the project. It may be possible to draw inspiration from
an [unfinished PR](https://github.com/jtdaugherty/vty/pull/1), Haskeline and
[`Win32-console`](https://hackage.haskell.org/package/Win32-console).


**Potential Mentors**: Jonathan Daugherty

**Difficulty**: Advanced
