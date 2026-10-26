---
title: CompareOptions
second_title: Aspose.Slides für C++ API-Referenz
description: Optionen für den Vergleich von Zeichenketten.
type: docs
weight: 430
url: /de/system.globalization/compareoptions/
---
## CompareOptions Enum

[String](../../system/string/) Vergleichsoptionen.
```cpp
enum class CompareOptions : int32_t
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| None | 0 | Keine speziellen Optionen. |
| IgnoreCase | 1 | Groß-/Kleinschreibung ignorieren. |
| IgnoreNonSpace | 2 | Nicht-Spacing-Kombinationszeichen ignorieren, z. B. Diakritika. |
| IgnoreSymbols | 4 | Leerzeichen, Satzzeichen und �hnliches einbeziehen. |
| IgnoreKanaType | 8 | Kana-Typ ignorieren (Japanisch). |
| IgnoreWidth | 16 | Zeichenbreite beim Vergleichen von Zeichenketten ignorieren. |
| OrdinalIgnoreCase | 268435456 | Ordinaler Vergleich, wobei der Unterschied in Groß-/Kleinschreibung ignoriert wird. |
| StringSort | 536870912 | String-Sortier-Algorithmus zum Vergleichen von Zeichen verwenden. |
| Ordinal | 1073741824 | UTF-Codes beim ersten Vergleich direkt vergleichen. |

## Siehe auch

* Namensraum [System::Globalization](../)
* Bibliothek [Aspose.Slides](../../)