---
title: GetColumnAlignment()
second_title: Aspose.Slides für C++ API-Referenz
description: Ermittelt die horizontale Ausrichtung der angegebenen Spalte
type: docs
weight: 248
url: /de/aspose.slides.mathtext/mathmatrix/getcolumnalignment/
---
## MathMatrix::GetColumnAlignment(int32_t) Methode


Ermittelt die horizontale Ausrichtung der angegebenen Spalte

```cpp
MathHorizontalAlignment Aspose::Slides::MathText::MathMatrix::GetColumnAlignment(int32_t columnIndex) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| columnIndex | **int32_t** | Nullbasierter Spaltenindex |

### Rückgabewert

Horizontale Ausrichtung der angegebenen Spalte
## Hinweise



Beispiel: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
auto alignment = matrix->GetColumnAlignment(0);
```

## Siehe auch

* Aufzählung [MathHorizontalAlignment](../../mathhorizontalalignment/)
* Klasse [MathMatrix](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)