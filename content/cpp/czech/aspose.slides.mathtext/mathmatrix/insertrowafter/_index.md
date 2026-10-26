---
title: InsertRowAfter()
second_title: Aspose.Slides pro C++ - referenční dokumentace API
description: Vloží nový řádek za zadaný. Počátečně jsou všechny prvky v novém řádku nulové.
type: docs
weight: 300
url: /cs/aspose.slides.mathtext/mathmatrix/insertrowafter/
---
## MathMatrix::InsertRowAfter(int32_t) metoda

Vloží nový řádek za zadaný. Počátečně jsou všechny prvky v novém řádku nulové.

```cpp
void Aspose::Slides::MathText::MathMatrix::InsertRowAfter(int32_t rowIndex) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| rowIndex | **int32_t** | Index řádku, za který se má vložit nový |

## Poznámky



Příklad: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertRowAfter(1);
```

## Viz také

* Třída [MathMatrix](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)