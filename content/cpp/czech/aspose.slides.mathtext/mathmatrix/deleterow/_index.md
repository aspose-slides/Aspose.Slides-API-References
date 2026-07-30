---
title: DeleteRow()
second_title: Aspose.Slides pro C++ API Reference
description: Odstraní zadaný řádek
type: docs
weight: 313
url: /cs/aspose.slides.mathtext/mathmatrix/deleterow/
---
## MathMatrix::DeleteRow(int32_t) metoda

Deletes the specified row
```cpp
void Aspose::Slides::MathText::MathMatrix::DeleteRow(int32_t rowIndex) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| rowIndex | **int32_t** | Nulový index řádku, který se má odstranit. |
## Poznámky



Příklad: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->DeleteRow(0);
```

## Viz také

* Třída [MathMatrix](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)