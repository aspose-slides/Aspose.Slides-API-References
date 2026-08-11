---
title: set_RepeatUntilNextClick()
second_title: Aspose.Slides لمرجع API C++
description: تحدد هذه الخاصية ما إذا كان التأثير سيتكرر حتى النقر التالي. اكتب bool.
type: docs
weight: 170
url: /ar/aspose.slides.animation/itiming/set_repeatuntilnextclick/
---
## ITiming::set_RepeatUntilNextClick(bool) طريقة


تحدد هذه الخاصية ما إذا كان التأثير سيتكرر حتى النقر التالي. اكتب **bool**.

```cpp
virtual void Aspose::Slides::Animation::ITiming::set_RepeatUntilNextClick(bool value)=0
```

## ملاحظات



```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptx");

// يحصل على تسلسل التأثيرات للشريحة الأولى
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence();

// يحصل على التأثير الأول من التسلسل الرئيسي.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// يغيّر توقيت/تكرار التأثير إلى "حتى نهاية الشريحة"
effect->get_Timing()->set_RepeatUntilNextClick(true);
```

## انظر أيضًا

* الفئة [ITiming](../)
* النطاق [Aspose::Slides::Animation](../../)
* المكتبة [Aspose.Slides](../../../)