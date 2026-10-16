# Project

A starting point for any kind of project: research, creative work, events,
operations, software and more. Use it to keep the project's purpose, work,
decisions and results understandable for everyone involved, including AI
contributors when they are part of the work.

## Start the project

1. Describe the purpose, intended result, scope and constraints in
   [PROJECT.md](PROJECT.md).
2. Set out the approach, important parts and responsibilities in
   [design](docs/design.md).
3. Record the first useful piece of work and next actions in
   [current work](docs/current-work.md).
4. Add supporting materials and checks as they become relevant. Small projects
   can combine records and leave unused folders empty.

## Continue the work

Start from the current agreement and active work. Follow their links to the
relevant materials, decisions and evidence. When understanding changes, update
the affected records and preserve the reasons behind important decisions.
Keep one current source for each agreement and link to detail where it already
lives.

Use [mocks and rehearsals](mocks/README.md) to explore an approach,
[tests and assessments](tests/README.md) to assess it, and
[evidence](evidence/README.md) to support findings. Record how the result will be
used, accepted and handed over in [delivery](docs/delivery.md).

## Versions and releases

Current baseline: **v1.0.0**. See the [changelog](CHANGELOG.md) for changes by
version and work planned for the next release.

Version the project as a whole using `MAJOR.MINOR.PATCH`. Choose the increment
by its effect on people using the result:

- **Major:** incompatible changes that require existing users or workflows to
  adapt.
- **Minor:** compatible additions to capabilities or guidance.
- **Patch:** corrections that preserve the intended behavior and agreements.

Keep changes under **Unreleased** until preparing a release. Review its scope
and evidence, finalize its dated changelog entry and version references, and
commit the intended contents. Create an annotated `vMAJOR.MINOR.PATCH` Git tag
on that exact commit. Released tags stay fixed; corrections use a new version.
A hosted release, when used, must refer to the same tag.

When starting a new project from this starter, begin a new release history and
update its version references. Record the starter version in
[PROJECT.md](PROJECT.md) when useful for tracing the starting point.

## Find project information

```text
project/
  README.md                # Where to start and how to work on the project
  AGENTS.md                # Instructions for AI contributors
  PROJECT.md               # Current purpose, scope, expectations and constraints
  CHANGELOG.md             # Released changes and work planned for the next release
  docs/
    README.md              # Guide to the project records
    design.md              # Approach, parts, interactions and responsibilities
    current-work.md        # Current work, findings, open questions and next actions
    decisions.md           # Decisions, reasons and changes
    delivery.md            # Delivery, acceptance, operation and handover
    elements/
      README.md            # Detail for parts that need their own records
  mocks/
    README.md              # Sketches, models, prototypes and rehearsals
  tests/
    README.md              # Checks, reviews and outcome assessments
  src/
    README.md              # Working materials used to produce the result
  evidence/
    README.md              # Selected results and references to supporting records
```
