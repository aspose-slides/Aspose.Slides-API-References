---
title: InsertColumnAfter()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Wstaw nową kolumnę po określonej. Początkowo wszystkie elementy w nowej kolumnie są null.
type: docs
weight: 339
url: /pl/aspose.slides.mathtext/mathmatrix/insertcolumnafter/
---
## MathMatrix::InsertColumnAfter(int32_t) metoda

Wstaw nową kolumnę po określonej. Początkowo wszystkie elementy w nowej kolumnie są null.

```cpp
void Aspose::Slides::MathText::MathMatrix::InsertColumnAfter(int32_t columnIndex) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| columnIndex | **int32_t** | Indeks kolumny, po której ma zostać wstawiona nowa |
## Uwagi

Przykład:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertColumnAfter(0);
```

## Zobacz także

* Klasa [MathMatrix](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)