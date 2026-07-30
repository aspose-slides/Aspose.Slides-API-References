---
title: SetColumnAlignment()
second_title: Aspose.Slides pro C++ referenci API
description: Nastaví vodorovné zarovnání určeného sloupce
type: docs
weight: 248
url: /cs/aspose.slides.mathtext/imathmatrix/setcolumnalignment/
---
## IMathMatrix::SetColumnAlignment(int32_t, MathHorizontalAlignment) metoda


Nastaví vodorovné zarovnání určeného sloupce

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::SetColumnAlignment(int32_t columnIndex, MathHorizontalAlignment val)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| columnIndex | **int32_t** | Index sloupce začínající od nuly |
| val | [MathHorizontalAlignment](../../mathhorizontalalignment/) | Nová hodnota vodorovného zarovnání určeného sloupce |
## Poznámky



Příklad: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->SetColumnAlignment(0, MathHorizontalAlignment::Left);
```

## Viz také

* Výčet [MathHorizontalAlignment](../../mathhorizontalalignment/)
* Třída [IMathMatrix](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)