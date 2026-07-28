---
title: get_Count()
second_title: Aspose.Slides dla C++ – referencja API
description: Zwraca liczbę podrzędnych elementów matematycznych faktycznie zawartych w kolekcji. Tylko do odczytu int32_t.
type: docs
weight: 1
url: /pl/aspose.slides.mathtext/mathblock/get_count/
---
## MathBlock::get_Count() metoda


Zwraca liczbę elementów matematycznych podrzędnych faktycznie znajdujących się w kolekcji. Tylko do odczytu **int32_t**.

```cpp
int32_t Aspose::Slides::MathText::MathBlock::get_Count() override
```

## Uwagi


Przykład: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
int32_t count = mathBlock->get_Count();
```

## Zobacz także

* Klasa [MathBlock](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)