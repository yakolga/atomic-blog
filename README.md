# atomic-blog

A small React demo project showing how to eliminate prop drilling using a custom provider and hook. The repository follows an "atomic" (component-oriented) structure and demonstrates a lightweight Context-based store with a custom hook for consuming state and actions.

[👉 Live version](https://yakolga.github.io/atomic-blog/)

## Goals
- Remove prop drilling across deeply nested components.
- Provide a simple, typed (optional) API: a Provider + custom hook.

## Features
- Centralized state provided via a custom Provider component.
- Consumption via a single custom hook (no props passed through intermediate components).
- Minimal, focused API surface to make migration from prop drilling straightforward.