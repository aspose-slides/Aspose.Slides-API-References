---
title: SetColumnAlignment()
second_title: Aspose.Slides für C++ API-Referenz
description: Setzt die horizontale Ausrichtung der angegebenen Spalte
type: docs
weight: 261
url: /de/aspose.slides.mathtext/mathmatrix/setcolumnalignment/
---
## MathMatrix::SetColumnAlignment(int32_t, MathHorizontalAlignment) Methode

Setzt die horizontale Ausrichtung der angegebenen Spalte

```cpp
void Aspose::Slides::MathText::MathMatrix::SetColumnAlignment(int32_t columnIndex, MathHorizontalAlignment val) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| columnIndex | **int32_t** | Nullbasierter Spaltenindex |
| val | [MathHorizontalAlignment](../../mathhorizontalalignment/) | Neuer Wert der horizontalen Ausrichtung der angegebenen Spalte |
## Bemerkungen



Beispiel: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->SetColumnAlignment(0, MathHorizontalAlignment::Left);
```

## Siehe auch

* Enum [MathHorizontalAlignment](../../mathhorizontalalignment/)
* Class [MathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)