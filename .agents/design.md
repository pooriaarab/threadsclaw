# ThreadsClaw design system

## Overview

ThreadsClaw has no implemented interface, command-line output, or archive format.
This document records evidence boundaries for future work.

The product concept requires a clear path from saved Threads content to an
agent-friendly archive. Exact interactions and presentation remain open.

## Colors

No palette, CSS token, terminal color, or semantic status color is implemented.

The thread spool emoji does not define canonical colors. Do not sample colors
from one platform's emoji artwork. Record exact tokens here after an interface
or command-line tool implements them.

## Typography

No font family, type scale, line-length rule, or archive text style exists.

Future text must keep source content, author data, timestamps, capture status,
and errors distinguishable. Do not require monospace or a web font without an
implemented need.

## Layout

No screen, panel, command output, or document layout exists.

Future presentation must preserve the relationship between a saved item and
its source metadata. It must show capture progress and failures clearly. Do not
declare a grid, pane model, density, or breakpoint before implementation.

## Elevation & Depth

No border, surface, shadow, overlay, or elevation scale is implemented.

Future depth may separate source content, archive metadata, and operation state.
Record exact rules only after code establishes them.

## Shapes

No logo geometry, radius, icon family, or control shape is implemented.

The thread spool emoji may remain a lightweight documentation cue. Do not treat
its vendor-specific geometry as a product asset.

## Components

The concept implies these functional parts:

- Source account or session state
- Saved-item capture operation
- Progress and error reporting
- Archive output
- Source metadata preservation
- Agent-readable result documentation

These are requirements, not implemented components. Authentication, storage,
file names, schemas, commands, and controls remain open choices.

## Do's and Don'ts

Do:

- Keep source content and archive metadata distinguishable.
- Make capture progress and failures explicit.
- Preserve evidence about where an archived item came from.
- Document a schema only after code implements and tests it.
- Treat private account data and saved content as sensitive.

Do not:

- Claim affiliation with Threads or Meta.
- Invent a scraper mechanism, command, schedule, or archive format.
- Derive a palette or logo from one emoji rendering.
- Claim an archive is complete or current without verification.
- Add `/brand` or `/design.md` routes without an owned production home.
