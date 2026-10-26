---
title: get_NoBreak()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "بدون انقطاع. تحدد هذه الخاصية الخاصية \"unbreakable\" على صندوق الكائن. عندما تكون true، لا يمكن حدوث فواصل سطر داخل الصندوق. قد يكون هذا مهمًا لمحاكيات العامل التي تتكون من أكثر من عامل ثنائي. عندما لا يتم تحديد هذا العنصر، يمكن حدوث فواصل داخل الصندوق. الإعداد الافتراضي: true"
type: docs
weight: 40
url: /ar/aspose.slides.mathtext/imathbox/get_nobreak/
---
## IMathBox::get_NoBreak() طريقة


بدون انقطاع. هذه الخاصية تحدد الخاصية \"unbreakable\" على صندوق الكائن. عندما تكون true، لا يمكن حدوث فواصل سطر داخل الصندوق. قد يكون هذا مهمًا لمحاكيات العامل التي تتكون من أكثر من عامل ثنائي. عندما لا يتم تحديد هذا العنصر، يمكن حدوث فواصل داخل الصندوق. الإعداد الافتراضي: true

```cpp
virtual bool Aspose::Slides::MathText::IMathBox::get_NoBreak()=0
```

## ملاحظات


مثال: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"**********")->ToBox();
box->set_NoBreak(false);
```

## انظر أيضا

* فئة [IMathBox](../)
* نطاق [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)