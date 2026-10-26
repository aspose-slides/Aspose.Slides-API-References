---
title: SetSubscript()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: ينشئ نصًا سفليًا
type: docs
weight: 66
url: /ar/aspose.slides.mathtext/mathelementbase/setsubscript/
---
## MathElementBase::SetSubscript(System::SharedPtr\<IMathElement\>) طريقة

ينشئ نصًا سفليًا

```cpp
System::SharedPtr<IMathSubscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubscript(System::SharedPtr<IMathElement> subscript) override
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | النص السفلي (مؤشر منخفض على اليمين) |

### قيمة الإرجاع

عنصر رياضي جديد من النوع [IMathSubscriptElement](../../imathsubscriptelement/)

## ملاحظات

مثال: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto index = System::MakeObject<MathematicalText>(u"i");
auto subscript = element->SetSubscript(index);
```

## MathElementBase::SetSubscript(System::String) طريقة

ينشئ نصًا سفليًا

```cpp
System::SharedPtr<IMathSubscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubscript(System::String subscript) override
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | النص السفلي (مؤشر منخفض على اليمين) |

### قيمة الإرجاع

عنصر رياضي جديد من النوع [IMathSubscriptElement](../../imathsubscriptelement/)

## ملاحظات

مثال: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto subscript = element->SetSubscript(u"i");
```

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IMathSubscriptElement](../../imathsubscriptelement/)
* فئة [IMathElement](../../imathelement/)
* فئة [MathElementBase](../)
* فئة [String](../../../system/string/)
* مساحة أسماء [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)