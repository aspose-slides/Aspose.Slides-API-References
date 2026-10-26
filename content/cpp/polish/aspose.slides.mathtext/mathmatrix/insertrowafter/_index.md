---
title: InsertRowAfter()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Wstaw nowy wiersz po określonym. Początkowo wszystkie elementy w nowym wierszu są nullem.
type: docs
weight: 300
url: /pl/aspose.slides.mathtext/mathmatrix/insertrowafter/
---
## MathMatrix::InsertRowAfter(int32_t) metoda

Wstaw nowy wiersz po określonym. Początkowo wszystkie elementy w nowym wierszu są nullem.

```cpp
void Aspose::Slides::MathText::MathMatrix::InsertRowAfter(int32_t rowIndex) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| rowIndex | **int32_t** | Indeks wiersza, po którym należy wstawić nowy |
## Uwagi


Przykład: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertRowAfter(1);
```

## Zobacz także

* Klasa [MathMatrix](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)