---
title: SetSubSuperscriptOnTheLeft()
second_title: مستندات API Aspose.Slides برای C++
description: زیرنویس و بالانویس را در سمت چپ ایجاد می‌کند
type: docs
weight: 118
url: /fa/aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft/
---
## IMathElement::SetSubSuperscriptOnTheLeft(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) متد

ایجاد زیرنویس و بالانویس در سمت چپ

```cpp
virtual System::SharedPtr<IMathLeftSubSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSubSuperscriptOnTheLeft(System::SharedPtr<IMathElement> subscript, System::SharedPtr<IMathElement> superscript)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | زیرنویس (اندیس پایین در سمت چپ) |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | بالانویس (اندیس بالا در سمت چپ) |

### مقدار برگشتی

عنصر ریاضی جدید از نوع [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)
## توضیحات

مثال: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto leftSubsuperscript = baseElement->SetSubSuperscriptOnTheLeft(subscript, superscript);
```

## IMathElement::SetSubSuperscriptOnTheLeft(System::String, System::String) متد

ایجاد زیرنویس و بالانویس در سمت چپ

```cpp
virtual System::SharedPtr<IMathLeftSubSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSubSuperscriptOnTheLeft(System::String subscript, System::String superscript)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | زیرنویس (اندیس پایین در سمت چپ) |
| superscript | [System::String](../../../system/string/) | بالانویس (اندیس بالا در سمت چپ) |

### مقدار برگشتی

عنصر ریاضی جدید از نوع [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)
## توضیحات

مثال: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto leftSubsuperscript = baseElement->SetSubSuperscriptOnTheLeft(u"i", u"j");
```

## مراجع

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)
* Class [IMathElement](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)