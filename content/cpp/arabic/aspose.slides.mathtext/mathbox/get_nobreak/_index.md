---
title: get_NoBreak()
second_title: Aspose.Slides لـ C++ مرجع API
description: "عدم الكسر هذه الخاصية تحدد الخاصية \"unbreakable\" على صندوق الكائن. عندما تكون true، لا يمكن حدوث فواصل أسطر داخل الصندوق. قد يكون هذا مهمًا لمحاكيات المشغلات التي تتألف من أكثر من مشغل ثنائي. عندما لا يتم تحديد هذا العنصر، يمكن أن تحدث فواصل داخل الصندوق. الافتراضي: true"
type: docs
weight: 40
url: /ar/aspose.slides.mathtext/mathbox/get_nobreak/
---
## MathBox::get_NoBreak() طريقة

الخاصية غير القابلة للكسر تحدد الخاصية "unbreakable" على صندوق الكائن. عندما تكون true، لا يمكن حدوث فواصل أسطر داخل الصندوق. قد يكون هذا مهمًا لمحاكيات المشغلات التي تتألف من أكثر من مشغل ثنائي. عندما لا يتم تحديد هذا العنصر، يمكن أن تحدث فواصل داخل الصندوق. الافتراضي: true

```cpp
bool Aspose::Slides::MathText::MathBox::get_NoBreak() override
```

## ملاحظات

مثال:
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"*****"));
box->set_NoBreak(false);
```

## انظر أيضًا

* الفئة [MathBox](../)
* المجال [Aspose::Slides::MathText](../../)
* المكتبة [Aspose.Slides](../../../)