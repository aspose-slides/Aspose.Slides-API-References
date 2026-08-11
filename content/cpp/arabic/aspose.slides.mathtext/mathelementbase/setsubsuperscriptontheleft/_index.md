---
title: SetSubSuperscriptOnTheLeft()
second_title: مرجع API الخاص بـ Aspose.Slides للغة C++
description: ينشئ نصًا فرعيًا ونصًا عُلويًا على اليسار
type: docs
weight: 105
url: /ar/aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft/
---
## MathElementBase::SetSubSuperscriptOnTheLeft(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) طريقة


ينشئ نصًا فرعيًا ونصًا عُلويًا على اليسار

```cpp
System::SharedPtr<IMathLeftSubSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubSuperscriptOnTheLeft(System::SharedPtr<IMathElement> subscript, System::SharedPtr<IMathElement> superscript) override
```


### المعلمات

| معامل | نوع | وصف |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | نص فرعي (مؤشر سفلي على اليسار) |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | نص علوي (مؤشر علوي على اليسار) |

### قيمة الإرجاع

عنصر رياضي جديد من النوع [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)
## ملاحظات



مثال: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto leftSubsuperscript = baseElement->SetSubSuperscriptOnTheLeft(subscript, superscript);
```

## MathElementBase::SetSubSuperscriptOnTheLeft(System::String, System::String) طريقة


ينشئ نصًا فرعيًا ونصًا عُلويًا على اليسار

```cpp
System::SharedPtr<IMathLeftSubSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubSuperscriptOnTheLeft(System::String subscript, System::String superscript) override
```


### المعلمات

| معامل | نوع | وصف |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | نص فرعي (مؤشر سفلي على اليسار) |
| superscript | [System::String](../../../system/string/) | نص علوي (مؤشر علوي على اليسار) |

### قيمة الإرجاع

عنصر رياضي جديد من النوع [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)
## ملاحظات



مثال: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto leftSubsuperscript = baseElement->SetSubSuperscriptOnTheLeft(u"i", u"j");
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)
* فئة [IMathElement](../../imathelement/)
* فئة [MathElementBase](../)
* فئة [String](../../../system/string/)
* نطاق [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)