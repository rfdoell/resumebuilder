# resumebuilder
This project is intended to help format and build pretty resumes from an "experience" database.

## Intent ##

The intent of this project is to help with the process of picking the right
experience for the typical, space-constrained resume. In initial scope, the
idea is to take a database of experiences, select the most fitting ones for an
opening, then build a pretty resume from them, using a template.

### MVP ###

The smallest thing to accomplish this would include:

* A flat-file "database", e.g., in YAML
* A single template file, e.g., in LaTeX, which has been converted to use
Jinja2 or similar
* A simple TUI which allows the user to pick what experiences fit the job at
hand
