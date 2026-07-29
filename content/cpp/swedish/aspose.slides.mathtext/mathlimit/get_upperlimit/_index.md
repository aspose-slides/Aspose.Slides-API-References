---
title: get_UpperLimit()
second_title: Aspose.Slides för C++ API-referens
description: Anger övre eller nedre gräns
type: docs
weight: 27
url: /sv/aspose.slides.mathtext/mathlimit/get_upperlimit/
---
## MathLimit::get_UpperLimit() metod


Anger övre eller nedre gräns

```cpp
bool Aspose::Slides::MathText::MathLimit::get_UpperLimit() override
```

## Anmärkningar


Exempel:
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"?\?\u001a?"));
limitElement->set_UpperLimit(false);
```

## Se även

* Klass [MathLimit](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)