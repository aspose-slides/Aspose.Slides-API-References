---
title: SetColumnsAlignment()
second_title: Aspose.Slides für C++ API-Referenz
description: Setzt die horizontale Ausrichtung der angegebenen Spalten
type: docs
weight: 274
url: /de/aspose.slides.mathtext/mathmatrix/setcolumnsalignment/
---
## MathMatrix::SetColumnsAlignment(int32_t, uint32_t, MathHorizontalAlignment) Methode

Setzt die horizontale Ausrichtung der angegebenen Spalten

```cpp
void Aspose::Slides::MathText::MathMatrix::SetColumnsAlignment(int32_t columnIndex, uint32_t columnsCount, MathHorizontalAlignment val) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| columnIndex | **int32_t** | Nullbasierter Index der ersten Spalte, deren Ausrichtung gesetzt wird |
| columnsCount | **uint32_t** | Die Anzahl der Spalten, für die die Ausrichtung festgelegt werden soll |
| val | [MathHorizontalAlignment](../../mathhorizontalalignment/) | Neuer Wert der horizontalen Ausrichtung der angegebenen Spalte |

## Hinweise

Beispiel:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->SetColumnsAlignment(0, 3, MathHorizontalAlignment::Left);
```

## Siehe auch

* Aufzählung [MathHorizontalAlignment](../../mathhorizontalalignment/)
* Klasse [MathMatrix](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)