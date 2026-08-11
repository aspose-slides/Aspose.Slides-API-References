---
title: SetSuperscript()
second_title: مرجع API Aspose.Slides للغة C++
description: ينشئ نصًا مرتفعًا
type: docs
weight: 92
url: /ar/aspose.slides.mathtext/imathelement/setsuperscript/
---
## IMathElement::SetSuperscript(System::SharedPtr\<IMathElement\>) طريقة

ينشئ نصًا مرتفعًا

```cpp
virtual System::SharedPtr<IMathSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSuperscript(System::SharedPtr<IMathElement> superscript)=0
```

### المعاملات

| معامل | نوع | وصف |
| --- | --- | --- |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | النص المرتفع (الرقم العلوي على اليمين) |

### قيمة الإرجاع

عنصر رياضي جديد من النوع [IMathSuperscriptElement](../../imathsuperscriptelement/)
## ملاحظات



مثال: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto index = System::MakeObject<MathematicalText>(u"4");
auto superscript = element->SetSuperscript(index);
```

## IMathElement::SetSuperscript(System::String) طريقة

ينشئ نصًا مرتفعًا

```cpp
virtual System::SharedPtr<IMathSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSuperscript(System::String superscript)=0
```

### المعاملات

| معامل | نوع | وصف |
| --- | --- | --- |
| superscript | [System::String](../../../system/string/) | النص المرتفع (الرقم العلوي على اليمين) |

### قيمة الإرجاع

عنصر رياضي جديد من النوع [IMathSuperscriptElement](../../imathsuperscriptelement/)
## ملاحظات



مثال: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto superscript = element->SetSuperscript(u"4");
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IMathSuperscriptElement](../../imathsuperscriptelement/)
* فئة [IMathElement](../)
* فئة [String](../../../system/string/)
* نطاق [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)