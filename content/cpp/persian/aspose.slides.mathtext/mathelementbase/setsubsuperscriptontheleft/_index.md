---
title: SetSubSuperscriptOnTheLeft()
second_title: Aspose.Slides برای C++ راهنمای API
description: ضرب‌نویس زیرین و بالایی را در سمت چپ ایجاد می‌کند
type: docs
weight: 105
url: /fa/aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft/
---
## MathElementBase::SetSubSuperscriptOnTheLeft(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) متد

ضرب‌نویس زیرین و بالایی را در سمت چپ ایجاد می‌کند

```cpp
System::SharedPtr<IMathLeftSubSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubSuperscriptOnTheLeft(System::SharedPtr<IMathElement> subscript, System::SharedPtr<IMathElement> superscript) override
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | زیرنویس (ایندکس پایین در سمت چپ) |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | بالانویس (ایندکس بالا در سمت چپ) |

### مقدار برگشت

عنصر ریاضی جدید از نوع [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)
## توضیحات



مثال: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto leftSubsuperscript = baseElement->SetSubSuperscriptOnTheLeft(subscript, superscript);
```

## MathElementBase::SetSubSuperscriptOnTheLeft(System::String, System::String) متد


ضرب‌نویس زیرین و بالایی را در سمت چپ ایجاد می‌کند

```cpp
System::SharedPtr<IMathLeftSubSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubSuperscriptOnTheLeft(System::String subscript, System::String superscript) override
```


### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | زیرنویس (ایندکس پایین در سمت چپ) |
| superscript | [System::String](../../../system/string/) | بالانویس (ایندکس بالا در سمت چپ) |

### مقدار برگشت

عنصر ریاضی جدید از نوع [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)
## توضیحات



مثال: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto leftSubsuperscript = baseElement->SetSubSuperscriptOnTheLeft(u"i", u"j");
```

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)
* کلاس [IMathElement](../../imathelement/)
* کلاس [MathElementBase](../)
* کلاس [String](../../../system/string/)
* فضای نام [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)