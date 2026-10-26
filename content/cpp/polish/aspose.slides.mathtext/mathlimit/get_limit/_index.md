---
title: get_Limit()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Argument limitu
type: docs
weight: 14
url: /pl/aspose.slides.mathtext/mathlimit/get_limit/
---
## MathLimit::get_Limit() metoda

Argument limitu

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathLimit::get_Limit() override
```

## Uwagi


Przykład:
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"?\?\u001a?"));
auto limitArg = limitElement->get_Limit();
```

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathElement](../../imathelement/)
* Klasa [MathLimit](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)