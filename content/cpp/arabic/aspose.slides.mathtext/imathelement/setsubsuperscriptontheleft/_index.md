---
title: SetSubSuperscriptOnTheLeft()
second_title: Aspose.Slides لـ C++ مرجع API
description: ينشئ نصًا سفليًا ونصًا علويًا على اليسار
type: docs
weight: 118
url: /ar/aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft/
---
## IMathElement::SetSubSuperscriptOnTheLeft(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) method

ينشئ نصًا سفليًا ونصًا علويًا على اليسار

```cpp
virtual System::SharedPtr<IMathLeftSubSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSubSuperscriptOnTheLeft(System::SharedPtr<IMathElement> subscript, System::SharedPtr<IMathElement> superscript)=0
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | نص سفلي (مؤشر سفلي على اليسار) |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | نص علوي (مؤشر علوي على اليسار) |

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

## IMathElement::SetSubSuperscriptOnTheLeft(System::String, System::String) method

ينشئ نصًا سفليًا ونصًا علويًا على اليسار

```cpp
virtual System::SharedPtr<IMathLeftSubSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSubSuperscriptOnTheLeft(System::String subscript, System::String superscript)=0
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | نص سفلي (مؤشر سفلي على اليسار) |
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

* تعريف النوع [SharedPtr](../../../system/sharedptr/)
* الفئة [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)
* الفئة [IMathElement](../)
* الفئة [String](../../../system/string/)
* النطاق [Aspose::Slides::MathText](../../)
* المكتبة [Aspose.Slides](../../../)