---
title: InsertColumnAfter()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Wstaw nową kolumnę po określonej. Początkowo wszystkie elementy w nowej kolumnie są null.
type: docs
weight: 326
url: /pl/aspose.slides.mathtext/imathmatrix/insertcolumnafter/
---
## IMathMatrix::InsertColumnAfter(int32_t) metoda

Wstaw nową kolumnę po określonej. Początkowo wszystkie elementy w nowej kolumnie są null.

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::InsertColumnAfter(int32_t columnIndex)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| columnIndex | **int32_t** | Indeks kolumny, po której należy wstawić nową |
## Uwagi



Przykład: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertColumnAfter(0);
```

## Zobacz także

* Klasa [IMathMatrix](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)