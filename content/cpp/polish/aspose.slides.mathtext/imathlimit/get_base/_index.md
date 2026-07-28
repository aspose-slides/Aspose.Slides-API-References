---
title: get_Base()
second_title: Aspose.Slides dla C++ - referencja API
description: Argument bazowy
type: docs
weight: 1
url: /pl/aspose.slides.mathtext/imathlimit/get_base/
---
## IMathLimit::get_Base() metoda

Argument bazowy

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathLimit::get_Base()=0
```

## Uwagi

Przykład: 
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"?\?\u001a?"));
auto baseArg = limitElement->get_Base();
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathElement](../../imathelement/)
* Klasa [IMathLimit](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)