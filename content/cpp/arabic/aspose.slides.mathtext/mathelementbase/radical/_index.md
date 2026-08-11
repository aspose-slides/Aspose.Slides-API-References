---
title: Radical()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يحدد الجذر الرياضي للدرجة المعطاة من الوسيط المحدد.
type: docs
weight: 118
url: /ar/aspose.slides.mathtext/mathelementbase/radical/
---
## MathElementBase::Radical(System::SharedPtr\<IMathElement\>) طريقة

يحدد الجذر الرياضي للدرجة المعطاة من الوسيط المحدد.

```cpp
System::SharedPtr<IMathRadical> Aspose::Slides::MathText::MathElementBase::Radical(System::SharedPtr<IMathElement> degree) override
```

### المعاملات

| معامل | نوع | وصف |
| --- | --- | --- |
| degree | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | وسيط الجذر |

### قيمة الإرجاع

مثيل جديد من النوع [IMathRadical](../../imathradical/)
## ملاحظات



مثال: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"2px");
auto degree = System::MakeObject<MathematicalText>(u"y");
auto radical = baseElement->Radical(degree);
```

## MathElementBase::Radical(System::String) طريقة

يحدد الجذر الرياضي للدرجة المعطاة من الوسيط المحدد.

```cpp
System::SharedPtr<IMathRadical> Aspose::Slides::MathText::MathElementBase::Radical(System::String degree) override
```

### المعاملات

| معامل | نوع | وصف |
| --- | --- | --- |
| degree | [System::String](../../../system/string/) | وسيط الجذر |

### قيمة الإرجاع

مثيل جديد من النوع [IMathRadical](../../imathradical/)
## ملاحظات



مثال: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"2px");
auto radical = baseElement->Radical(u"3");
```

## انظر أيضاً

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IMathRadical](../../imathradical/)
* فئة [IMathElement](../../imathelement/)
* فئة [MathElementBase](../)
* فئة [String](../../../system/string/)
* نطاق [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)