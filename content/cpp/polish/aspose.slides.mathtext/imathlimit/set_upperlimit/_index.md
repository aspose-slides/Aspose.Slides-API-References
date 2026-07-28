---
title: set_UpperLimit()
second_title: Aspose.Slides dla C++ referencja API
description: Określa górny lub dolny limit
type: docs
weight: 40
url: /pl/aspose.slides.mathtext/imathlimit/set_upperlimit/
---
## IMathLimit::set_UpperLimit(bool) metoda


Określa górny lub dolny limit

```cpp
virtual void Aspose::Slides::MathText::IMathLimit::set_UpperLimit(bool value)=0
```

## Uwagi


Przykład: 
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"?\?\u001a?"));
limitElement->set_UpperLimit(false);
```

## Zobacz także

* Klasa [IMathLimit](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)