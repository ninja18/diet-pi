Produce an implementation plan for: $ARGUMENTS

Work read-only. Do not edit, write, or create any file, and do not run commands that change state
(no installs, no migrations, no git commands other than read-only inspection).

Explore enough of the repository to be concrete, then output a plan with exactly these sections:

1. Goal - the outcome in one or two sentences.
2. Current behaviour - what the relevant code does today, with file paths and line references.
3. Proposed design - the approach at the level of modules, interfaces, data and schema, and
   contracts, not file-by-file code. Name the key decision and the alternative you rejected, with
   the reason.
4. Diagram - one Mermaid diagram, only when the change touches three or more components or actors,
   or the control flow is non-obvious. Pick the type that fits: sequence for interaction between
   parts, flowchart for branching logic, class or ER for data, state for a state machine. Keep
   labels short; put anything longer in prose below the diagram. Avoid semicolons in labels (they
   break the parser), and keep the diagram no wider than the terminal, or pi shows plain text
   instead. Omit this section otherwise.
5. Files to change - each path, and one line on why.
6. Steps - ordered, each with the check that proves it worked (a test name, a command, or an
   observable behaviour).
7. Out of scope - what this plan deliberately does not cover.
8. Risks and unknowns - what could break, and what you could not determine from the code.
9. Questions - anything you need me to decide before starting.

Keep it under a page. Name real paths, real symbols, and real commands. If the change is small enough
that a plan adds nothing, say so in one line and propose the single next action instead.
