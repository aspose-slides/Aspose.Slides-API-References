---
title: InsertRowAfter()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Vloží novou řadu za zadanou. Počátečně jsou všechny prvky v nové řadě nulové.
type: docs
weight: 287
url: /cs/aspose.slides.mathtext/imathmatrix/insertrowafter/
---
## IMathMatrix::InsertRowAfter(int32_t) metoda

Vloží novou řadu za zadanou. Počátečně jsou všechny prvky v nové řadě nulové.

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::InsertRowAfter(int32_t rowIndex)=0
```

### Arguments

| Parametr | Typ | Popis |
| --- | --- | --- |
| rowIndex | **int32_t** | Index řádku, za který se vloží nový |
## Poznámky



Příklad: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertRowAfter(1);
```

## Viz také

* Třída [IMathMatrix](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)