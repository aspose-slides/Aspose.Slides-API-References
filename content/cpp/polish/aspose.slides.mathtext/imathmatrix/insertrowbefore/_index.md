---
title: InsertRowBefore()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Wstaw nowy wiersz przed określonym. Początkowo wszystkie elementy w nowym wierszu są puste.
type: docs
weight: 274
url: /pl/aspose.slides.mathtext/imathmatrix/insertrowbefore/
---
## IMathMatrix::InsertRowBefore(int32_t) metoda


Wstaw nowy wiersz przed określonym. Początkowo wszystkie elementy w nowym wierszu są puste.

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::InsertRowBefore(int32_t rowIndex)=0
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

* Klasa [IMathMatrix](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)