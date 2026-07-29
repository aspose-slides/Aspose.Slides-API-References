---
title: SetRange()
second_title: Aspose.Slides för C++ API-referens
description: Ställ in diagrammets dataintervall. Serier och kategorier uppdateras baserat på det nya dataintervallet. Om antalet serier i dataintervallet är större än antalet serier i diagramdata, läggs ytterligare serier med samma typ som den sista serien i den aktuella samlingen till i slutet av samlingen.
type: docs
weight: 157
url: /sv/aspose.slides.charts/ichartdata/setrange/
---
## IChartData::SetRange(System::String) metod

Ställ in diagrammets dataintervall. Serier och kategorier kommer att uppdateras baserat på det nya dataintervallet. Om antalet serier i dataintervall är större än antalet serier i diagramdata, kommer ytterligare serier med samma typ som den sista serien i den aktuella samlingen att läggas till i slutet av samlingen.

```cpp
virtual void Aspose::Slides::Charts::IChartData::SetRange(System::String formula)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| formula | [System::String](../../../system/string/) | Formeln för cellernas dataintervall. T.ex.: \"Sheet1!$A$1:$C$4\" , \"SomeSheetName!A1:B100\", \"Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5\". |

## Se även

* Klass [String](../../../system/string/)
* Klass [IChartData](../)
* Namnrymd [Aspose::Slides::Charts](../../)
* Bibliotek [Aspose.Slides](../../../)