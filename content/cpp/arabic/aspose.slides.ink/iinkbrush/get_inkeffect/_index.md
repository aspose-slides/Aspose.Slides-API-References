---
title: get_InkEffect()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "يُحصل على نوع تأثير الحبر (مثل Galaxy، Gold، Silver) الذي يحدد النمط البصري لضربة الحبر. يتم استخراج القيمة من خاصية الفرشاة \"inkEffects\". إذا لم يتم تحديد أي تأثير معروف، يتم إرجاع InkEffectType::NotDefined."
type: docs
weight: 53
url: /ar/aspose.slides.ink/iinkbrush/get_inkeffect/
---
## IInkBrush::get_InkEffect() طريقة


يحصل على نوع تأثير الحبر (مثل Galaxy، Gold، Silver) الذي يحدد النمط البصري لخط الحبر. يتم استخراج القيمة من خاصية الفرشاة \"inkEffects\". إذا لم يتم تحديد أي تأثير معروف، يتم إرجاع [InkEffectType::NotDefined](../../inkeffecttype/).

```cpp
virtual InkEffectType Aspose::Slides::Ink::IInkBrush::get_InkEffect()=0
```

## ملاحظات


مثال: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");
System::SharedPtr<Ink> ink = System::AsCast<Ink>(pres->get_Slide(0)->get_Shape(0));
System::SharedPtr<IInkBrush> brush = ink->get_Traces()->idx_get(0)->get_Brush();
System::Console::WriteLine(u"InkEffects = {0}", brush->get_InkEffect());
```

## انظر أيضًا

* Enum [InkEffectType](../../inkeffecttype/)
* Class [IInkBrush](../)
* Namespace [Aspose::Slides::Ink](../../)
* Library [Aspose.Slides](../../../)