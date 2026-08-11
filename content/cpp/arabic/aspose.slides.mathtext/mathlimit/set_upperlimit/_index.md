---
title: set_UpperLimit()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحدد الحد العُلوي أو السُفلي
type: docs
weight: 40
url: /ar/aspose.slides.mathtext/mathlimit/set_upperlimit/
---
## MathLimit::set_UpperLimit(bool) طريقة


يحدد الحد العُلوي أو السُفلي

```cpp
void Aspose::Slides::MathText::MathLimit::set_UpperLimit(bool value) override
```

## ملاحظات


مثال:
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"?\?\u001a?"));
limitElement->set_UpperLimit(false);
```

## انظر أيضًا

* فئة [MathLimit](../)
* نطاق [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)