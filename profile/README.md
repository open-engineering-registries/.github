# Open Engineering Registries

The authoritative registries of the Open Engineering ecosystem.

Open Engineering Registries define where engineering knowledge is published, discovered, identified, and resolved. They provide the trusted catalogs that allow engineering assets to be uniquely identified, searched, validated, and reused across organizations, runtimes, and systems.

Rather than storing engineering artifacts themselves, registries maintain the metadata that makes those artifacts discoverable.

⸻

## Purpose

Open Engineering is built around independently managed repositories containing definitions, elements, applications, runtimes, operating systems, stories, characters, and many other reusable assets.

Registries provide the glue that connects them.

They answer questions such as:

* Which Element Definition defines this Element?
* Where is this Runtime published?
* Which versions exist?
* Which organization owns this package?
* Which identifiers resolve to which resources?
* Which APIs or services expose this capability?
* Which package should be used for a particular purpose?

⸻

## Registries in the Open Engineering Architecture
```
                    Open Engineering Ecosystem
                               │
        ┌──────────────────────┴──────────────────────┐
        │                                             │
 Engineering Assets                           Open Engineering Registries
        │                                             │
        ▼                                             ▼
Definitions                               Identifier Registry
Elements                                  Package Registry
Stories                                   Runtime Registry
Characters                                Application Registry
Applications                              Service Registry
Runtimes                                  Organization Registry
Operating Systems                         Namespace Registry
Execution Platforms                       Version Registry
Motion Pictures                           ...
```
Engineering repositories remain the system of record for their own contents.

Registries provide the system of discovery.

⸻

## Responsibilities

Open Engineering Registries are responsible for:

* publishing metadata
* resolving identifiers
* indexing engineering assets
* maintaining discoverability
* supporting dependency resolution
* enabling interoperability
* exposing search capabilities
* validating references
* supporting tooling and automation

⸻

## Registry Types

A registry may catalog many kinds of engineering resources, including:

* Element Definitions
* Elements
* Stories
* Characters
* Rigs
* Motion Pictures
* Applications
* Runtimes
* Operating Systems
* Execution Platforms
* Packages
* APIs
* Services
* Organizations
* Namespaces
* Conventions
* Ontologies

Future Open Engineering conventions may define additional registry categories without changing the overall architecture.

⸻

## Relationship to Other Organizations

Open Engineering Registries complement other organizations across the ecosystem.
```
Organization	Responsibility
Open Engineering Ontologies	Defines meaning
Open Engineering Conventions	Defines standards
Open Engineering Elements	Defines reusable engineering building blocks
Open Engineering Applications	Defines engineering applications
Open Engineering Runtimes	Executes applications
Open Engineering Operating Systems	Provides execution environments
Open Engineering Execution Platforms	Deploys complete engineering solutions
Open Engineering Registries	Makes everything discoverable
```
⸻

Example Workflow
```
Developer
     │
     ▼
Publishes Runtime
     │
     ▼
Registry indexes metadata
     │
     ▼
Search
     │
     ▼
Resolver
     │
     ▼
Package downloaded
     │
     ▼
Runtime executed
```
Registries enable engineers, AI assistants, developer tools, and automation platforms to locate engineering assets without needing prior knowledge of where they are hosted.

⸻

## Design Principles

Open Engineering Registries follow several core principles:

* Authoritative — Registry entries point to canonical engineering assets.
* Federated — Organizations can publish independently while remaining discoverable.
* Open — Registry metadata is designed to be openly consumable.
* Composable — Registries integrate naturally with other Open Engineering components.
* Version-aware — Multiple versions of assets can coexist.
* Tool-friendly — Registries are designed for automation, APIs, CLIs, IDEs, and AI agents.
* Identifier-first — Assets are referenced through stable identifiers rather than implementation details.

⸻

## Part of the Open Engineering Ecosystem

Open Engineering Registries are one of the foundational organizations within the Open Engineering ecosystem, enabling discovery and interoperability across engineering assets while allowing repositories to remain independently owned and managed.

Together with Ontologies, Conventions, Queries, Resolvers, and Runtimes, Registries help transform a collection of repositories into a connected engineering platform.
