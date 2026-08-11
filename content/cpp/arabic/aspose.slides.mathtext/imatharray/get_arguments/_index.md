---
title: get_Arguments()
second_title: Aspose.Slides لواجهة برمجة التطبيقات (API) للغة C++
description: مجموعة عناصر المصفوفة
type: docs
weight: 1
url: /ar/aspose.slides.mathtext/imatharray/get_arguments/
---
## IMathArray::get_Arguments() طريقة

مجموعة العناصر في المصفوفة

```cpp
virtual System::SharedPtr<IMathElementCollection> Aspose::Slides::MathText::IMathArray::get_Arguments()=0
```

## ملاحظات

مثال:
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->get_Arguments()->Add(System::MakeObject<MathematicalText>(u"item2"));
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IMathElementCollection](../../imathelementcollection/)
* فئة [IMathArray](../)
* نطاق [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)