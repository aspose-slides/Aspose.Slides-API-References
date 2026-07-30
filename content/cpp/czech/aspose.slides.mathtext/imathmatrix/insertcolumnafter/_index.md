---
title: InsertColumnAfter()
second_title: Aspose.Slides pro C++ – reference API
description: Vloží nový sloupec za zadaný. Počátečně jsou všechny prvky v novém sloupci nulové.
type: docs
weight: 326
url: /cs/aspose.slides.mathtext/imathmatrix/insertcolumnafter/
---
## IMathMatrix::InsertColumnAfter(int32_t) metoda


Vloží nový sloupec za zadaným. Počátečně jsou všechny prvky v novém sloupci nulové.

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::InsertColumnAfter(int32_t columnIndex)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| columnIndex | **int32_t** | Index sloupce, za který se vloží nový |
## Poznámky



Příklad: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertColumnAfter(0);
```

## Viz také

* Třída [IMathMatrix](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)