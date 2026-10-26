---
title: WarningType
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Reprezentuje typ ostrzeżenia.
type: docs
weight: 92
url: /pl/aspose.slides.warnings/warningtype/
---
## WarningType enum

Reprezentuje typ ostrzeżenia.

```cpp
enum class WarningType
```

### Wartości

| Nazwa | Wartość | Opis |
| --- | --- | --- |
| SourceFileCorruption | 0 | Wykryto problem w dokumencie źródłowym, co sprawia, że bardzo prawdopodobne jest, że dokument nie będzie można otworzyć, jeśli zostanie zapisany w jego oryginalnym formacie. |
| DataLoss | 1 | Tekst/wykres/obraz lub inne dane będą całkowicie brakować zarówno w drzewie dokumentu po załadowaniu, jak i w utworzonym dokumencie po zapisaniu. |
| MajorFormattingLoss | 2 | Znaczna utrata formatowania. |
| MinorFormattingLoss | 3 | Mniejsza utrata formatowania. |
| CompatibilityIssue | 4 | To jest znany problem, który uniemożliwi otwarcie dokumentu przez niektóre przeglądarki lub wcześniejsze wersje przeglądarek. |
| UnexpectedContent | 99 | Niektóre treści w dokumencie źródłowym nie mogły zostać rozpoznane (tj. są nieobsługiwane); może to powodować problemy lub prowadzić do utraty danych/formatowania. |

## Zobacz także

* Przestrzeń nazw [Aspose::Slides::Warnings](../)
* Biblioteka [Aspose.Slides](../../)