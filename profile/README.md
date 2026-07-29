# Swift ECMA

Swift implementations of Ecma International specifications — a per-authority organization of [swift-standards](https://github.com/swift-standards), Layer 2 of the [Swift Institute](https://github.com/swift-institute) ecosystem.

## What this is

One package per specification, named `swift-ecma-<number>`. Each package implements its source document as literally as possible — parsing, validation, and formatting enforced by Swift's type system — and defines its own namespace (`ECMA_48`). Where several specifications govern one subject, the unifying `swift-*-standard` package lives in [swift-standards](https://github.com/swift-standards).

> Swift ECMA is an independent open-source project. It is not affiliated with, endorsed by, or sponsored by Ecma International.

## Find packages

The complete, current package list is available in the [repositories tab](https://github.com/orgs/swift-ecma/repositories). Search for `swift-ecma-` to find packages by their specification number; each repository description carries the specification's full title.

## Status

Public alpha. Maintained by [Coen ten Thije Boonkkamp](https://github.com/coenttb) — contributions welcome via pull request.

## License

All packages use the Apache License 2.0.
