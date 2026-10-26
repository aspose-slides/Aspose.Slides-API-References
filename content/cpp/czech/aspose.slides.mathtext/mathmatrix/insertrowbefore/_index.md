---
title: InsertRowBefore()
second_title: Aspose.Slides pro C++ referenci API
description: Vložte nový řádek před zadaný. Původně jsou všechny prvky v novém řádku null.
type: docs
weight: 287
url: /cs/aspose.slides.mathtext/mathmatrix/insertrowbefore/
---
## MathMatrix::InsertRowBefore(int32_t) metoda

Vložte nový řádek před zadaný. Původně jsou všechny prvky v novém řádku null.

```cpp
void Aspose::Slides::MathText::MathMatrix::InsertRowBefore(int32_t rowIndex) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| rowIndex | **int32_t** | Index řádku, před kterým se má vložit nový |
## Poznámky



Příklad:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertRowBefore(1);
```

## Viz také

* Třída [MathMatrix](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)