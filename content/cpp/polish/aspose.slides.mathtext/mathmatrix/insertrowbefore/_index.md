---
title: InsertRowBefore()
second_title: Aspose.Slides dla C++ - referencja API
description: Wstaw nowy wiersz przed określonym. Początkowo wszystkie elementy w nowym wierszu są nullem.
type: docs
weight: 287
url: /pl/aspose.slides.mathtext/mathmatrix/insertrowbefore/
---
## MathMatrix::InsertRowBefore(int32_t) metoda


Wstaw nowy wiersz przed określonym. Początkowo wszystkie elementy w nowym wierszu są nullem.

```cpp
void Aspose::Slides::MathText::MathMatrix::InsertRowBefore(int32_t rowIndex) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| rowIndex | **int32_t** | Indeks wiersza, przed którym ma zostać wstawiony nowy |
## Uwagi



Przykład: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertRowBefore(1);
```

## Zobacz także

* Klasa [MathMatrix](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)