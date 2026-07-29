# Python for R Programmers: A One-Week Workshop
*2026-07-29 10:00 PDT*

A short workshop for statisticians and data analysts who are
already fluent in R and want to become productive in Python.
Every Python construct is introduced by contrast with its R
counterpart. Five days, one chapter each.

## Structure

- **Day 1** Orientation and Setup: the Python Mental Model
- **Day 2** Data Structures and Control Flow
- **Day 3** NumPy and pandas: Data Frames the Python Way
- **Day 4** Visualization, Modeling, and the Scientific Stack
- **Day 5** Reproducible Python Projects and Interoperability

Each day is approximately 1 hour of lecture content + 2 hours
of homework with worked solutions. No examinations.

## Build

```bash
quarto render
```

The cover is generated procedurally:

```bash
Rscript images/build-cover.R
```

## Position in the series

This workshop assumes the R fluency of *R for Biostatistics: A
One-Week Boot Camp* and teaches Python by translation from it.
It sits alongside these companion volumes:

- *R for Biostatistics: A One-Week Boot Camp* — the R language
- *Git and GitHub for Biostatistics: A One-Week Boot Camp* —
  version control
- *Statistical Computing in the Age of AI* — methods and
  computing
- *Applied Generative AI for Health Sciences Research* —
  generative AI

## License

Prose: CC BY-NC-ND 4.0. Code: CC0 1.0.
