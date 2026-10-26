---
title: Radical()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحدد الجذر الرياضي للدرجة المعطاة من الوسيط المحدد.
type: docs
weight: 131
url: /ar/aspose.slides.mathtext/imathelement/radical/
---
## IMathElement::Radical(System::SharedPtr\<IMathElement\>) طريقة

يحدد الجذر الرياضي للدرجة المعطاة من الوسيط المحدد.

```cpp
virtual System::SharedPtr<IMathRadical> Aspose::Slides::MathText::IMathElement::Radical(System::SharedPtr<IMathElement> degree)=0
```

### المعاملات

| معامل | نوع | الوصف |
| --- | --- | --- |
| degree | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | وسيط الجذر |

### قيمة الإرجاع

كائن جديد من النوع [IMathRadical](../../imathradical/)

## ملاحظات



مثال: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"2px");
auto degree = System::MakeObject<MathematicalText>(u"y");
auto radical = baseElement->Radical(degree);
```

## IMathElement::Radical(System::String) طريقة

يحدد الجذر الرياضي للدرجة المعطاة من الوسيط المحدد.

```cpp
virtual System::SharedPtr<IMathRadical> Aspose::Slides::MathText::IMathElement::Radical(System::String degree)=0
```

### المعاملات

| معامل | نوع | الوصف |
| --- | --- | --- |
| degree | [System::String](../../../system/string/) | وسيط الجذر |

### قيمة الإرجاع

كائن جديد من النوع [IMathRadical](../../imathradical/)

## ملاحظات



مثال: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"2px");
auto radical = baseElement->Radical(u"3");
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IMathRadical](../../imathradical/)
* فئة [IMathElement](../)
* فئة [String](../../../system/string/)
* نطاق [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)