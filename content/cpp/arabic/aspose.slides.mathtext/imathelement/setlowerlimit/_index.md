---
title: SetLowerLimit()
second_title: Aspose.Slides لـ C++ مرجع API
description: يأخذ الحد الأدنى
type: docs
weight: 157
url: /ar/aspose.slides.mathtext/imathelement/setlowerlimit/
---
## IMathElement::SetLowerLimit(System::SharedPtr\<IMathElement\>) طريقة

تأخذ الحد الأدنى

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathElement::SetLowerLimit(System::SharedPtr<IMathElement> limit)=0
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | الحد |

### قيمة الإرجاع

نسخة جديدة من النوع [IMathLimit](../../imathlimit/)

## ملاحظات



مثال: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"lim");
auto limitValue = System::MakeObject<MathematicalText>(u"\U0001d45b→∞");
auto limitElement = baseElement->SetLowerLimit(limitValue);
```

## IMathElement::SetLowerLimit(System::String) طريقة

تأخذ الحد الأدنى

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathElement::SetLowerLimit(System::String limit)=0
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| limit | [System::String](../../../system/string/) | الحد |

### قيمة الإرجاع

نسخة جديدة من النوع [IMathLimit](../../imathlimit/)

## ملاحظات



مثال: 
```cpp
System::SharedPtr<IMathElement> baseElement = System::MakeObject<MathematicalText>(u"lim");
auto limitElement = baseElement->SetLowerLimit(u"\U0001d45b→∞");
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IMathLimit](../../imathlimit/)
* فئة [IMathElement](../)
* فئة [String](../../../system/string/)
* مساحة اسم [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)