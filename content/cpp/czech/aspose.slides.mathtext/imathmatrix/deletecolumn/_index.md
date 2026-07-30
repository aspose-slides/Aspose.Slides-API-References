---
title: DeleteColumn()
second_title: Aspose.Slides pro C++ referenční dokumentace API
description: Odstraní zadaný sloupec
type: docs
weight: 339
url: /cs/aspose.slides.mathtext/imathmatrix/deletecolumn/
---
## IMathMatrix::DeleteColumn(int32_t) metoda


Odstraní zadaný sloupec

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::DeleteColumn(int32_t columnIndex)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| columnIndex | **int32_t** | Nulový index sloupce, který se má odstranit. |
## Poznámky



Příklad: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->DeleteColumn(0);
```

## Viz také

* Třída [IMathMatrix](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)