---
title: get_Limit()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Argument limitu
type: docs
weight: 14
url: /pl/aspose.slides.mathtext/imathlimit/get_limit/
---
## IMathLimit::get_Limit() metoda


Argument limitu

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathLimit::get_Limit()=0
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
* Klasa [IMathLimit](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)