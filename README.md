# Job Interview Skills

How to act in a job interview from first handshake to follow-up: research, your stories, common and tough questions, phone and video interviews, body language, questions to ask, salary and offers.

Part of the [Yaaddi](https://github.com/yaaddi-courses) course catalog: a spaced-repetition flashcard course, ready to build and validate with the standard Yaaddi course tooling.

## Sources and accuracy

The advice follows widely taught interview practice (STAR answers, preparation, follow-up, salary research). Norms differ by country, industry and employer, so adapt it to your situation.

This course is study help, not professional advice. See the [Terms of use](https://courses.yaaddi.com/terms/).

## Structure

- `meta.json`: course metadata (title, description, cover image, version)
- `source/`: authoring source (`meta.csv`, `units.csv`, `cards.csv`, `glossary.csv`, images)
- `plan.csv`: table of contents (not shipped in the zip)
- the built `.zip`: generated from `source/` via `build_course_zip.py`

## Editing this course

```bash
python validate_course.py . --source
python build_course_zip.py .
```
