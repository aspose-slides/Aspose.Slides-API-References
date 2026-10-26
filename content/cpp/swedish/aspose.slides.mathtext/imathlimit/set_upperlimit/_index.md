---
title: set_UpperLimit()
second_title: Aspose.Slides för C++ API-referens
description: Anger övre eller nedre gräns
type: docs
weight: 40
url: /sv/aspose.slides.mathtext/imathlimit/set_upperlimit/
---
## IMathLimit::set_UpperLimit(bool) method

Anger övre eller nedre gräns

```cpp
virtual void Aspose::Slides::MathText::IMathLimit::set_UpperLimit(bool value)=0
```

## Anmärkningar

Exempel: 
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"?\?\u001a?"));
limitElement->set_UpperLimit(false);
```

## Se även

* Klass [IMathLimit](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)