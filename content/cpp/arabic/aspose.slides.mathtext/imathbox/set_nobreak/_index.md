---
title: set_NoBreak()
second_title: مرجع API لـ Aspose.Slides for C++
description: "بدون فاصل. تحدد هذه الخاصية الخاصية \"unbreakable\" على صندوق الكائن. عندما تكون true، لا يمكن حدوث فواصل أسطر داخل الصندوق. قد يكون هذا مهمًا لمحاكيات المشغل التي تتألف من أكثر من مشغل ثنائي. عندما لا يتم تحديد هذا العنصر، يمكن حدوث فواصل داخل الصندوق. الافتراضي: true"
type: docs
weight: 53
url: /ar/aspose.slides.mathtext/imathbox/set_nobreak/
---
## IMathBox::set_NoBreak(bool) طريقة

بدون فاصل. تحدد هذه الخاصية الخاصية \"unbreakable\" على صندوق الكائن. عندما تكون true، لا يمكن حدوث فواصل أسطر داخل الصندوق. قد يكون هذا مهمًا لمحاكيات المشغل التي تتألف من أكثر من مشغل ثنائي. عندما لا يتم تحديد هذا العنصر، يمكن حدوث فواصل داخل الصندوق. الافتراضي: true

```cpp
virtual void Aspose::Slides::MathText::IMathBox::set_NoBreak(bool value)=0
```

## ملاحظات

مثال: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"**********")->ToBox();
box->set_NoBreak(false);
```

## انظر أيضًا

* الفئة [IMathBox](../)
* النطاق [Aspose::Slides::MathText](../../)
* المكتبة [Aspose.Slides](../../../)