---
title: GetColumnAlignment()
second_title: Aspose.Slides pro C++ API Reference
description: Získá vodorovné zarovnání zadaného sloupce
type: docs
weight: 235
url: /cs/aspose.slides.mathtext/imathmatrix/getcolumnalignment/
---
## IMathMatrix::GetColumnAlignment(int32_t) metoda


Získá vodorovné zarovnání zadaného sloupce

```cpp
virtual MathHorizontalAlignment Aspose::Slides::MathText::IMathMatrix::GetColumnAlignment(int32_t columnIndex)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| columnIndex | **int32_t** | Index sloupce začínající od nuly |

### Vrácená hodnota

Horizontální zarovnání zadaného sloupce
## Poznámky



Příklad: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
auto alignment = matrix->GetColumnAlignment(0);
```

## Viz také

* Enum [MathHorizontalAlignment](../../mathhorizontalalignment/)
* Třída [IMathMatrix](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)