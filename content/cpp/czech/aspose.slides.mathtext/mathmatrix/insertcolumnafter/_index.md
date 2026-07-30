---
title: InsertColumnAfter()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Vloží nový sloupec za zadaný. Počátečně jsou všechny prvky v novém sloupci nulové.
type: docs
weight: 339
url: /cs/aspose.slides.mathtext/mathmatrix/insertcolumnafter/
---
## MathMatrix::InsertColumnAfter(int32_t) metoda

Vloží nový sloupec za zadaný. Počátečně jsou všechny prvky v novém sloupci nulové.

```cpp
void Aspose::Slides::MathText::MathMatrix::InsertColumnAfter(int32_t columnIndex) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| columnIndex | **int32_t** | Index sloupce, za který se má vložit nový |
## Poznámky

Příklad: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertColumnAfter(0);
```

## Viz také

* Třída [MathMatrix](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)