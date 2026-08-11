---
title: SetUpperLimit()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يأخذ الحد الأعلى
type: docs
weight: 144
url: /ar/aspose.slides.mathtext/imathelement/setupperlimit/
---
## IMathElement::SetUpperLimit(System::SharedPtr\<IMathElement\>) طريقة

يأخذ الحد الأعلى

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathElement::SetUpperLimit(System::SharedPtr<IMathElement> limit)=0
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | limit |

### قيمة الإرجاع

كائن جديد من النوع [IMathLimit](../../imathlimit/)

## ملاحظات

مثال: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"y");
auto limitValue = System::MakeObject<MathematicalText>(u"y?>1");
auto limitElement = baseElement->SetUpperLimit(limitValue);
```

## IMathElement::SetUpperLimit(System::String) طريقة

يأخذ الحد الأعلى

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathElement::SetUpperLimit(System::String limit)=0
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| limit | [System::String](../../../system/string/) | limit |

### قيمة الإرجاع

كائن جديد من النوع [IMathLimit](../../imathlimit/)

## ملاحظات

مثال: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"y");
auto limitElement = baseElement->SetUpperLimit(u"y?>1");
```

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IMathLimit](../../imathlimit/)
* فئة [IMathElement](../)
* فئة [String](../../../system/string/)
* مساحة الأسماء [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)