---
title: DeleteRow()
second_title: Referencja API Aspose.Slides dla C++
description: Usuwa określony wiersz
type: docs
weight: 300
url: /pl/aspose.slides.mathtext/imathmatrix/deleterow/
---
## IMathMatrix::DeleteRow(int32_t) metoda


Usuwa określony wiersz

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::DeleteRow(int32_t rowIndex)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| rowIndex | **int32_t** | Indeks wiersza do usunięcia, liczony od zera. |
## Uwagi



Przykład: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->DeleteRow(0);
```

## Zobacz także

* Klasa [IMathMatrix](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)