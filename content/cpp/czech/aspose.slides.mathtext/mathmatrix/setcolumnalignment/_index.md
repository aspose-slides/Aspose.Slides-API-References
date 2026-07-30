---
title: SetColumnAlignment()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Nastaví vodorovné zarovnání určeného sloupce
type: docs
weight: 261
url: /cs/aspose.slides.mathtext/mathmatrix/setcolumnalignment/
---
## MathMatrix::SetColumnAlignment(int32_t, MathHorizontalAlignment) metoda

Nastaví vodorovné zarovnání zadaného sloupce

```cpp
void Aspose::Slides::MathText::MathMatrix::SetColumnAlignment(int32_t columnIndex, MathHorizontalAlignment val) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| columnIndex | **int32_t** | Index sloupce počínaje nulou |
| val | [MathHorizontalAlignment](../../mathhorizontalalignment/) | Nová hodnota vodorovného zarovnání zadaného sloupce |
## Poznámky



Příklad: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->SetColumnAlignment(0, MathHorizontalAlignment::Left);
```

## Viz také

* Enum [MathHorizontalAlignment](../../mathhorizontalalignment/)
* třída [MathMatrix](../)
* jmenný prostor [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)