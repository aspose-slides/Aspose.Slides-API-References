---
title: HandleRepeatedSpaces
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Określa, jak należy obsługiwać powtarzające się zwykłe znaki spacji podczas eksportu do Markdown.
type: docs
weight: 937
url: /pl/aspose.slides.export/handlerepeatedspaces/
---
## HandleRepeatedSpaces enum

Określa, jak należy obsługiwać powtarzające się zwykłe znaki spacji podczas eksportu do Markdown.

```cpp
enum class HandleRepeatedSpaces
```

### Wartości

| Nazwa | Wartość | Opis |
| --- | --- | --- |
| None | 0 | Wszystkie spacje są zachowywane jako zwykłe znaki spacji bez żadnych zmian. Nie stosuje się żadnej transformacji, a wielokrotne kolejne spacje są eksportowane w niezmienionej formie. |
| AlternateSpacesToNbsp | 1 | Konwertuje sekwencje dwóch lub więcej kolejnych zwykłych spacji, naprzemiennie zamieniając je na zwykłe znaki spacji i niełamiące się spacje (**&nbsp;**). Pierwsza spacja jest zawsze zachowywana jako zwykła spacja. |
| MultipleSpacesToNbsp | 2 | Konwertuje sekwencje dwóch lub więcej kolejnych zwykłych spacji, zachowując pierwszą spację jako zwykły znak spacji i zamieniając wszystkie kolejne spacje na niełamiące się spacje (**&nbsp;**). |

## Zobacz także

* Przestrzeń nazw [Aspose::Slides::Export](../)
* Biblioteka [Aspose.Slides](../../)