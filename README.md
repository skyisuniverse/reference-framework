# reference-framework

## ToDo

- [ ] Create reference (s) similar to [mdn](https://developer.mozilla.org/en-US/) (e.g. [JavaScript reference](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference)) for each domain of [adr](https://architecture-decision-records.vercel.app/en)

Since we already have [adr](https://architecture-decision-records.vercel.app/en) as a portal, it could make sense to implement a reference portal as a feature of it, rather than creating a separate portal site. It could be a domain switcher (Architecture / Reference).

How could it look like? e.g.:

- Fusion reference
- Nano-assembly reference
- etc.

We could assume a single programming language that would suffice for requirements and complexity of all domains (which could possibly require implementation of corresponding features as a part of its design). For example, similar to how JS's objects, arrays and functions (etc.) allow to create servers and clients, there could be objects for Plasma control in Fusion, or Nanobot Swarm ops in Nano-Assembly.

---

Reference is luxury in a way, assuming that:

- it provides a possibility to achieve tangible, visible results quickly and easily
- is built on top of tech ecosystem that enables it (including hardware, software, techstacks, runtimes, etc.) (e.g. in case of [JS](https://developer.mozilla.org/en-US/docs/Web/JavaScript) - [V8](https://v8.dev/))

It could possibly be that each of [adr](https://architecture-decision-records.vercel.app/en)'s domains is supplemented with open-source ecosystem of tools that make it easy to implement things in a programmatic way similar to JS (assuming that all necessary underlying complexity for it is implemented as a part of tech foundation layers (physical / software architecture))

---

## Reference & knowledge base

[Reference](./reference.md) should not be confused with a knowledge base.

- (Programming language) **Reference** is a documentation designed for developers that explicitly defines a language’s basic syntax, built-in components, and runtime semantics.
- A **knowledge base** is a library of articles that stores (any kind of) information, data, documentation on any topic (preferably in an easily understandable way)

---

It makes sense to have:

- **adr portal** for architecture decision records
- **knowledge base app** as tech encyclopedia
- **reference portal** for language references

Should we implement all three in one app with switching across these three domains? Or make three separate sites?
