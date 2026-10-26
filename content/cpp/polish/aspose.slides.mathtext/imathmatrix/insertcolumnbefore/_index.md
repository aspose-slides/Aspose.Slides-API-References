---
title: InsertColumnBefore()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Wstaw nową kolumnę przed określoną. Początkowo wszystkie elementy w nowej kolumnie są null.
type: docs
weight: 313
url: /pl/aspose.slides.mathtext/imathmatrix/insertcolumnbefore/
---
## IMathMatrix::InsertColumnBefore(int32_t) metoda


Wstaw nową kolumnę przed wskazaną. Początkowo wszystkie elementy w nowej kolumnie są null.

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::InsertColumnBefore(int32_t columnIndex)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| columnIndex | **int32_t** | Indeks kolumny, przed którą ma zostać wstawiona nowa |
## Uwagi



Przykład: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertColumnBefore(0);
```

## Zobacz także

* Klasa [IMathMatrix](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)