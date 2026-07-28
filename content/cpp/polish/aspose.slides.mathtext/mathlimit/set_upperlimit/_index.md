---
title: set_UpperLimit()
second_title: Aspose.Slides dla C++ Dokumentacja API
description: Określa górny lub dolny limit
type: docs
weight: 40
url: /pl/aspose.slides.mathtext/mathlimit/set_upperlimit/
---
## MathLimit::set_UpperLimit(bool) metoda


Określa górny lub dolny limit

```cpp
void Aspose::Slides::MathText::MathLimit::set_UpperLimit(bool value) override
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