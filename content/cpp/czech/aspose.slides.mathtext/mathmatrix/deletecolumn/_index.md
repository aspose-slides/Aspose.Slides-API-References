---
title: DeleteColumn()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Odstraní zadaný sloupec
type: docs
weight: 352
url: /cs/aspose.slides.mathtext/mathmatrix/deletecolumn/
---
## MathMatrix::DeleteColumn(int32_t) metoda


Odstraní zadaný sloupec

```cpp
void Aspose::Slides::MathText::MathMatrix::DeleteColumn(int32_t columnIndex) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| columnIndex | **int32_t** | Nulový index sloupce, který má být smazán. |
## Poznámky



Příklad: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->DeleteColumn(0);
```

## Viz také

* Třída [MathMatrix](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)