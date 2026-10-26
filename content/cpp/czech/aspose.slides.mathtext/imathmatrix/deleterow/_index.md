---
title: DeleteRow()
second_title: Reference API pro Aspose.Slides pro C++
description: Smaže určený řádek
type: docs
weight: 300
url: /cs/aspose.slides.mathtext/imathmatrix/deleterow/
---
## IMathMatrix::DeleteRow(int32_t) metoda


Smaže určený řádek

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::DeleteRow(int32_t rowIndex)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| rowIndex | **int32_t** | Nulový index řádku, který má být smazán. |
## Poznámky



Příklad: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->DeleteRow(0);
```

## Viz také

* Třída [IMathMatrix](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)