---
title: get_UpperLimit()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Określa górny lub dolny limit
type: docs
weight: 27
url: /pl/aspose.slides.mathtext/mathlimit/get_upperlimit/
---
## MathLimit::get_UpperLimit() metoda

Określa górny lub dolny limit

```cpp
bool Aspose::Slides::MathText::MathLimit::get_UpperLimit() override
```

## Uwagi

Przykład:
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"?\?\u001a?"));
limitElement->set_UpperLimit(false);
```

## Zobacz także

* Klasa [MathLimit](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)