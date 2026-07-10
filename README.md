# Exam Prep — 4e Secondaire

Practice quiz app for Québec Ministère exam preparation (Math SN + Science).

## Structure

```
Exam Prep 4e Secondaire/
├── math/
│   ├── exams/          ← Source PDFs (one copy, never duplicate)
│   └── quizzes/        ← Generated HTML quiz files
├── science/
│   ├── exams/          ← Source PDFs
│   └── quizzes/        ← Generated HTML quiz files
└── shared/
    └── assets/         ← Shared CSS, JS, images
```

## Source Files

| File | Subject | Source |
|---|---|---|
| math/exams/sn4-pratique1-examen-eleve-1.pdf | Math SN — Pratique 1 | Puissance 4 SN, Grand Duc |

## Quizzes

| File | Based On | Status |
|---|---|---|
| math/quizzes/pratique1-quiz.html | sn4-pratique1-examen-eleve-1.pdf | In progress |

## Live Quizzes

| Quiz | Subject | Link |
|---|---|---|
| Pratique 1 | Math SN 4e sec | [Jouer →](https://saherwafai.github.io/exam-prep-4e-secondaire/math/pratique1-quiz.html) |

## Rules
- One source PDF per exam — never duplicate
- All quiz HTML files go in docs/math/ or docs/science/
- GitHub Pages serves from the docs/ folder
- Hosted at: https://saherwafai.github.io/exam-prep-4e-secondaire/
