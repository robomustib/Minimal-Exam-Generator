# Minimal-Exam-Generator / Einfacher Klausurgenerator
A minimal web-based exam generator that allows teachers or students to create randomized practice exams from a simple CSV file containing questions and point values. The web-app automatically generates a set of questions that match an exact total score (e.g., 50 points) and exports the result as a PDF.

Ein Einfacher webbasierter Klausurgenerator, mit dem Lehrende oder Lernende aus einer einfachen CSV-Datei mit Fragen und Punktwerten zufällige Übungsprüfungen erstellen können. Die WebApp generiert automatisch einen Satz von Fragen, die einer bestimmten Gesamtpunktzahl (z. B. 50 Punkten) entsprechen, und exportiert das Ergebnis als PDF.



## Features

- Upload your own CSV file (Format: `Question;Points`) by using example_utf8.csv
- Generate a randomized exam that matches your chosen total score
- Preview the generated exam in the browser
- Export the exam as a PDF
- Works fully client-side


## Languages

- 🇩🇪 German (`einfacher-klausurgenerator.html`)
- 🇺🇸 English (`minimal-exam-generator.html`)

 
## Example CSV Format

```csv
What is Newton's second law?;5
Explain Ohm’s Law.;8
Describe the energy conversion in a wind turbine.;7
```

## Demo
Click here to try out:
[Einfacher Klausurgenerator / German ](https://www.mustafa-bilgin.de/klausurgenerator)

```bash
git clone https://github.com/robomustib/Minimal-Exam-Generator.git
cd Minimal-Exam-Generator
open minimal-exam-generator.html
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
