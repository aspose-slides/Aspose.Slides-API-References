---
title: InsertRowBefore()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Vloží nový řádek před zadaný. Veškeré prvky v novém řádku jsou zpočátku nulové.
type: docs
weight: 274
url: /cs/aspose.slides.mathtext/imathmatrix/insertrowbefore/
---
## IMathMatrix::InsertRowBefore(int32_t) metoda

Vloží nový řádek před určený. Všechny prvky v novém řádku jsou zpočátku nulové.

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::InsertRowBefore(int32_t rowIndex)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| rowIndex | **int32_t** | Index řádku, před který se má vložit nový |
## Poznámky



Příklad:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertRowBefore(1);
```

## Viz také

* Třída [IMathMatrix](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)