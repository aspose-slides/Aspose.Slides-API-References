---
title: InsertColumnBefore()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Wstaw nową kolumnę przed określoną. Początkowo wszystkie elementy w nowej kolumnie są null.
type: docs
weight: 326
url: /pl/aspose.slides.mathtext/mathmatrix/insertcolumnbefore/
---
## MathMatrix::InsertColumnBefore(int32_t) metoda


Wstaw nową kolumnę przed wskazaną. Początkowo wszystkie elementy w nowej kolumnie są null.

```cpp
void Aspose::Slides::MathText::MathMatrix::InsertColumnBefore(int32_t columnIndex) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| columnIndex | **int32_t** | Indeks kolumny, przed którą ma być wstawiona nowa |
## Uwagi



Przykład: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertColumnBefore(0);
```

## Zobacz także

* Klasa [MathMatrix](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)