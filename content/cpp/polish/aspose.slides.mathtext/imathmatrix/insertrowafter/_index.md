---
title: InsertRowAfter()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Wstaw nowy wiersz po wskazanym. Początkowo wszystkie elementy w nowym wierszu są null.
type: docs
weight: 287
url: /pl/aspose.slides.mathtext/imathmatrix/insertrowafter/
---
## IMathMatrix::InsertRowAfter(int32_t) metoda


Wstaw nowy wiersz po wskazanym. Początkowo wszystkie elementy w nowym wierszu są null.

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::InsertRowAfter(int32_t rowIndex)=0
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

* Klasa [IMathMatrix](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)