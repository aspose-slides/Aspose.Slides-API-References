---
title: GetColumnAlignment()
second_title: Aspose.Slides für C++ API Referenz
description: Ermittelt die horizontale Ausrichtung der angegebenen Spalte
type: docs
weight: 235
url: /de/aspose.slides.mathtext/imathmatrix/getcolumnalignment/
---
## IMathMatrix::GetColumnAlignment(int32_t) Methode

Ermittelt die horizontale Ausrichtung der angegebenen Spalte

```cpp
virtual MathHorizontalAlignment Aspose::Slides::MathText::IMathMatrix::GetColumnAlignment(int32_t columnIndex)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| columnIndex | **int32_t** | Nullbasierter Spaltenindex |

### Rückgabewert

Horizontale Ausrichtung der angegebenen Spalte
## Anmerkungen



Beispiel: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
auto alignment = matrix->GetColumnAlignment(0);
```

## Siehe auch

* Aufzählung [MathHorizontalAlignment](../../mathhorizontalalignment/)
* Klasse [IMathMatrix](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)