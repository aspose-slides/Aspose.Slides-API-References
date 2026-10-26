---
title: InsertColumnBefore()
second_title: Aspose.Slides pro C++ API Reference
description: Vloží nový sloupec před určený. Počátečně jsou všechny prvky v novém sloupci null.
type: docs
weight: 326
url: /cs/aspose.slides.mathtext/mathmatrix/insertcolumnbefore/
---
## MathMatrix::InsertColumnBefore(int32_t) metoda

Vloží nový sloupec před zadaný. Počátečně jsou všechny prvky v novém sloupci null.

```cpp
void Aspose::Slides::MathText::MathMatrix::InsertColumnBefore(int32_t columnIndex) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| columnIndex | **int32_t** | Index sloupce, před který se má vložit nový |

## Poznámky

Příklad:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertColumnBefore(0);
```

## Viz také

* Třída [MathMatrix](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)