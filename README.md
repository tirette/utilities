# Utilities

A library with utilities which are often reused throughout various Tirette's projects.

[ideology](#ideology)

[usage](#usage)

This package is a library used to easily organize blocks of code which are often reused across multiple Tirette projects.

---

## Ideology
To keep Tirette's code bases as future proof as possible we reduce mentions of third-party modules to a minimum. Only third-party modules necessary for the working of the core of the project are allowed. We will implement as many features as possible without the use of third-parties as long as this is viable. This does not mean we reinvent the wheel though. We have repositories like this one to bridge the gap between what we can implement ourself and the heavy lifting done by others. Where we create our own native API to connect our projects to existing third-parties. An API wall as we like to call it. This approach has a few benefits over intertwining third-party code with our own:
1. This allows us to maintain an API of our own and design it in a way that seems most proficient to our cause, separate from our main projects.
2. This makes us independent of third-parties or unsusceptible to deprecations, breaking changes or cluttering the code-base with workarounds or bug fixes that should actually be handled by those third-parties.
3. This allows us to map multiple third-parties to a single API and flexibly swap between them.