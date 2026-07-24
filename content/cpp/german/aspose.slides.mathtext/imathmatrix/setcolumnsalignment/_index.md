---
title: SetColumnsAlignment()
second_title: Aspose.Slides für C++ API-Referenz
description: Setzen Sie die horizontale Ausrichtung der angegebenen Spalten
type: docs
weight: 261
url: /de/aspose.slides.mathtext/imathmatrix/setcolumnsalignment/
---
## IMathMatrix::SetColumnsAlignment(int32_t, uint32_t, MathHorizontalAlignment) Methode

Set the horizontal alignment of the specified columns

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::SetColumnsAlignment(int32_t columnIndex, uint32_t columnsCount, MathHorizontalAlignment val)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| columnIndex | **int32_t** | Nullbasierter Index der ersten Spalte, deren Ausrichtung festgelegt wird |
| columnsCount | **uint32_t** | Die Anzahl der Spalten, für die die Ausrichtung festgelegt wird |
| val | [MathHorizontalAlignment](../../mathhorizontalalignment/) | Neuer Wert der horizontalen Ausrichtung der angegebenen Spalte |
## Bemerkungen



Beispiel: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->SetColumnsAlignment(0, 3, MathHorizontalAlignment::Left);
```

## Siehe auch

* Aufzählung [MathHorizontalAlignment](../../mathhorizontalalignment/)
* Klasse [IMathMatrix](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)