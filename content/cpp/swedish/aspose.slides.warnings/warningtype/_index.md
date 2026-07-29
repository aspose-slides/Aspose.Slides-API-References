---
title: WarningType
second_title: Aspose.Slides för C++ API-referens
description: Representerar en typ av varning.
type: docs
weight: 92
url: /sv/aspose.slides.warnings/warningtype/
---
## WarningType enum

Representerar en typ av varning.

```cpp
enum class WarningType
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| SourceFileCorruption | 0 | Ett problem har upptäckts i källdokumentet som gör det mycket sannolikt att dokumentet inte kan öppnas om det sparas i sitt ursprungliga format. |
| DataLoss | 1 | Text/diagram/bild eller annan data kommer att saknas helt från antingen dokumentträdet efter inläsning, eller det skapade dokumentet efter sparning. |
| MajorFormattingLoss | 2 | Större formateringsförlust. |
| MinorFormattingLoss | 3 | Mindre formateringsförlust. |
| CompatibilityIssue | 4 | Detta är ett känt problem som kommer att hindra dokumentet från att öppnas av vissa användaragenter, eller tidigare versioner av användaragenter. |
| UnexpectedContent | 99 | Viss innehåll i källdokumentet kunde inte identifieras (dvs. stöds ej), detta kan eller kan inte orsaka problem eller leda till data-/formateringsförlust. |

## Se också

* Namnrymd [Aspose::Slides::Warnings](../)
* Bibliotek [Aspose.Slides](../../)