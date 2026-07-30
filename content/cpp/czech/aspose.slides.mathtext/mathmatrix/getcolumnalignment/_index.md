---
title: GetColumnAlignment()
second_title: Aspose.Slides pro C++ API Reference
description: Získá vodorovné zarovnání určeného sloupce
type: docs
weight: 248
url: /cs/aspose.slides.mathtext/mathmatrix/getcolumnalignment/
---
## MathMatrix::GetColumnAlignment(int32_t) metoda


Získá vodorovné zarovnání určeného sloupce

```cpp
MathHorizontalAlignment Aspose::Slides::MathText::MathMatrix::GetColumnAlignment(int32_t columnIndex) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| columnIndex | **int32_t** | Index sloupce začínající od nuly |

### Návratová hodnota

Vodorovné zarovnání určeného sloupce
## Poznámky



Příklad: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
auto alignment = matrix->GetColumnAlignment(0);
```

## Viz také

* Výčet [MathHorizontalAlignment](../../mathhorizontalalignment/)
* Třída [MathMatrix](../)
* Obor názvů [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)