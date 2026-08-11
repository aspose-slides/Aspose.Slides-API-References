---
title: get_Rewind()
second_title: مرجع واجهة برمجة التطبيقات Aspose.Slides للغة C++
description: هذه الخاصية تحدد ما إذا كان التأثير سيُعيد التشغيل عند انتهاء تشغيله. اقرأ bool.
type: docs
weight: 235
url: /ar/aspose.slides.animation/timing/get_rewind/
---
## Timing::get_Rewind() طريقة


هذه الخاصية تحدد ما إذا كان التأثير سيُعيد التشغيل عند انتهاء تشغيله. اقرأ **bool**.

```cpp
bool Aspose::Slides::Animation::Timing::get_Rewind() override
```

## ملاحظات



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// الحصول على تسلسل التأثيرات للشريحة الأولى
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slide(0)->get_Timeline()->get_MainSequence();

// الحصول على أول تأثير من التسلسل الرئيسي.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// تفعيل Timing/Rewind للتأثير.
effect->get_Timing()->set_Rewind(true);
```

## انظر أيضًا

* فئة [Timing](../)
* نطاق [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)