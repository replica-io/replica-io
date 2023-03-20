<div align="center">
    <img src="doc/img/logo.png" alt="Logo" />
    <h1>Replica_IO</h1>
</div>

Replica_IO is a framework for composing practical distributed
replication mechanisms.

## Status 🌱

This project is in its early stages. It's being developed entirely in
the open from day one. So more stuff will follow. Stay tuned! 👀

## Purpose 🌟

The purpose of this project is to advance computing by making highly
reliable distributed systems more practical to implement.

More and more we depend on increasingly complex computing systems.
Therefore, we ought to make such critical systems highly reliable.
Distributed systems are potentially much more reliable than
centralized ones. However, anyone who tried implementing
fault-tolerant distributed systems knows how hard it is in practice.

Practical solutions should be both efficient and easy to use.
Unfortunately, distributed systems tend to be less efficient, and they
are notoriously complex. Often we can tolerate moderate decrease in
efficiency, but reliability is crucial for critical systems we largely
depend upon.

Nevertheless, complex problems can have neat solutions that are not
only efficient, but also easy to properly apply in practice.
Discovering and developing those solutions obviously requires
significant effort. This project is making such effort.

## Goal 🎯

The goal of this project is to develop a well-supported and widely
used state-of-the-art framework for building distributed replication
mechanisms, thus greatly facilitating practical implementation of
highly reliable distributed systems.

Specifically, the framework should provide a carefully designed
collection of primitives, components, tools, and guidelines for
developing core mechanisms of fault-tolerant distributed systems, such
as state machine replication or distributed coordination services.
Sensibly chosen principles guide the process of designing and
implementing generic components, such as consensus or various kinds of
broadcast. These components get constructed out of the corresponding
protocol logic, more simple components, and fundamental primitives,
such as asynchronous communication or timer abstractions. Unified
means of combination ensure great composability of the elements. Fine
modularity together with built-in capabilities for tracing and
controlling execution enable effective debugging, validation, and
analysis. Powerful and convenient tools allow effectively utilizing
those features. Clear guidelines help using the framework properly by
explaining its features on simple, easy-to-follow examples.

This framework is conceived as generic and independent from any
specific target system or use case, embracing different flavors of
fault-tolerance, consistency, and synchrony models, e.g. strong, weak,
or eventual consistency under CFT, BFT, or hybrid models with strong,
partial, or no synchrony assumption. It is particularly concerned not
only with immediate safety guarantees, but also with ensuring rigorous
liveness guarantees and memory bounds, as well as further features
highly desired in practice, such as bootstrapping procedures, online
reconfiguration, recovery of faulty nodes, and ability to recover from
a massive system crash (durability).

Last, but not least, it should be highly ergonomic so that developers
enjoy playing with it while effectively solving their problems.

## Approach 🤓

The approach of this project is best characterized as follows:

  * _open:_ publicly available, transparent, and collaborative;
  * _understandable:_ intuitive, well documented, and easy to use;
  * _flexible:_ generic, modular, and easy to integrate;
  * _holistic:_ taking into account all relevant aspects;
  * _innovative:_ discovering and using state-of-the-art techniques;
  * _quality-oriented:_ carefully designed, implemented, and verified;
  * _iterative:_ starting small — growing strong, delivering value
    regularly and persistently.

## Contributing 🙏

The project's goal is quite ambitious, so your support is more than
welcome! 🤗

If you are also excited about this project, there are many ways you
can get involved. A good start is to subscribe for notifications,
check and participate in open issues, pull requests, discussions.
Please ask questions, suggest ideas, report problems, submit changes!

## License ⚖️

Source code is licensed under the [Apache License, Version
2.0](LICENSE).

Documentation is licensed under the [Creative Commons Attribution 4.0
International License][cc-40].

[cc-40]: http://creativecommons.org/licenses/by/4.0/
