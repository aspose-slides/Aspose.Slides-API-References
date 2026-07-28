---
title: get_UpperLimit()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Określa górny lub dolny limit
type: docs
weight: 27
url: /pl/aspose.slides.mathtext/imathlimit/get_upperlimit/
---
## IMathLimit::get_UpperLimit() metoda


Określa górny lub dolny limit

```cpp
virtual bool Aspose::Slides::MathText::IMathLimit::get_UpperLimit()=0
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