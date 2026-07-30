---
title: InsertColumnBefore()
second_title: Aspose.Slides pro C++ reference API
description: Vložte nový sloupec před určený. Počátečně jsou všechny prvky v novém sloupci null.
type: docs
weight: 313
url: /cs/aspose.slides.mathtext/imathmatrix/insertcolumnbefore/
---
## IMathMatrix::InsertColumnBefore(int32_t) metoda


Vložte nový sloupec před zadaný. Počátečně jsou všechny prvky v novém sloupci null.

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::InsertColumnBefore(int32_t columnIndex)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| columnIndex | **int32_t** | Index sloupce, před kterým se má vložit nový |
## Poznámky



Příklad: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertColumnBefore(0);
```

## Viz také

* Třída [IMathMatrix](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)