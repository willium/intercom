# Intercom

Seamless, typesafe inter-process communication for modern JavaScript environments.

## Overview

Intercom is a lightweight, zero-dependency library designed to simplify communication between different JavaScript contexts, primarily focused on Web Workers and inter-process communication (IPC). It provides a type-safe, isomorphic API that works across various build systems and frameworks.

## Key Features

- Full TypeScript support with optional Zod schema validation
- Isomorphic design - write once, run on either side
- Efficient worker pool management and task marshalling
- Zero dependencies
- Support for transferable objects
- Compatible with major build systems: webpack, Turbopack, Vite

## Goals

Intercom aims to provide a unified, type-safe approach to inter-process communication in JavaScript environments. By abstracting away the complexities of worker management, serialization, and IPC, Intercom allows developers to focus on building features rather than managing communication infrastructure.

## Planned Features

- Electron IPC support
- Framework-specific wrappers (React, Svelte, etc.)
- Enhanced performance optimizations for large-scale applications
- Extended support for various serialization formats

## Status

Intercom is currently in active development. We're focused on establishing a solid core API and ensuring compatibility with major build systems and environments.

## Contributing

We welcome contributions and feedback. Please see our issues page for current development priorities.

## License

Intercom is released under the MIT License.
