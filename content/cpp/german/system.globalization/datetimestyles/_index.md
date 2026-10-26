---
title: DateTimeStyles
second_title: Aspose.Slides für C++ API Referenz
description: Definiert Optionen für die Datums- und Zeitformatierung. Bit-Flags.
type: docs
weight: 456
url: /de/system.globalization/datetimestyles/
---
## DateTimeStyles Enum


Definiert Optionen für die Datums- und Zeitformatierung. Bit-Flags.

```cpp
enum class DateTimeStyles : int32_t
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| None | 0 | Standard. |
| AllowLeadingWhite | 1 | Ignoriert führende Leerzeichen. |
| AllowTrailingWhite | 2 | Ignoriert nachlaufende Leerzeichen. |
| AllowInnerWhite | 4 | Ignoriert innere Leerzeichen. |
| AllowWhiteSpaces | n/a | Ignoriert alle Leerzeichen. |
| NoCurrentDateDefault | 8 | Beim Parsen einer Datums-/Uhrzeitzeichenkette, wenn alle Jahr/Monat/Tag fehlen, wird das Standarddatum auf 0001/1/1 gesetzt, anstatt auf das aktuelle Jahr/Monat/Tag. |
| AdjustToUniversal | 16 | Beim Parsen einer Datums-/Uhrzeitzeichenkette, wenn ein Zeitzonenangabe (\"GMT\",\"Z\",\"+xxxx\", \"-xxxx\") vorhanden ist, wird die geparste Zeit auf GMT angepasst. |
| AssumeLocal | 32 | Wenn keine Zeitzone angegeben ist, wird die lokale Zeitzone verwendet. |
| AssumeUniversal | 64 | Wenn keine Zeitzone angegeben ist, wird UTC verwendet. |
| RoundtripKind | 128 | Versucht beizubehalten, ob die Eingabe nicht spezifiziert, lokal oder UTC ist. |

## Siehe auch

* Namensraum [System::Globalization](../)
* Bibliothek [Aspose.Slides](../../)