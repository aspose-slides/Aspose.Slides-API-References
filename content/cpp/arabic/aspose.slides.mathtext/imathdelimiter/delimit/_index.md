---
title: Delimit()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحدد حدود الوسائط باستخدام حرف الفاصل المحدد
type: docs
weight: 144
url: /ar/aspose.slides.mathtext/imathdelimiter/delimit/
---
## IMathDelimiter::Delimit(char16_t) method

يقوم بتحديد حدود الوسائط باستخدام حرف الفاصلة المحدد

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathDelimiter::Delimit(char16_t separatorCharacter)=0
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| separatorCharacter | char16_t | حرف الفاصل |

### قيمة الإرجاع

هذا الكائن بعد تطبيق حرف الفاصل

## ملاحظات



مثال: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->Delimit(u'|');
```

## انظر أيضا

* Typedef [SharedPtr](../../../system/sharedptr/)
* الفئة [IMathDelimiter](../)
* مساحة الاسم [Aspose::Slides::MathText](../../)
* المكتبة [Aspose.Slides](../../../)