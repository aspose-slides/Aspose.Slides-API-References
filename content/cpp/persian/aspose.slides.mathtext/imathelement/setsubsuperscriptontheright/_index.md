---
title: SetSubSuperscriptOnTheRight()
second_title: مرجع API Aspose.Slides برای C++
description: زیرنویس و بالانویس را در سمت راست ایجاد می‌کند
type: docs
weight: 105
url: /fa/aspose.slides.mathtext/imathelement/setsubsuperscriptontheright/
---
## IMathElement::SetSubSuperscriptOnTheRight(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) متد

زیرنویس و بالانویس را در سمت راست ایجاد می‌کند

```cpp
virtual System::SharedPtr<IMathRightSubSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSubSuperscriptOnTheRight(System::SharedPtr<IMathElement> subscript, System::SharedPtr<IMathElement> superscript)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | زیرنویس (شاخص پایین در سمت راست) |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | بالانویس (شاخص بالا در سمت راست) |

### مقدار بازگشت

عنصر ریاضی جدید از نوع [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)
## توضیحات



مثال: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto subsuperscript = baseElement->SetSubSuperscriptOnTheRight(subscript, superscript);
```

## IMathElement::SetSubSuperscriptOnTheRight(System::String, System::String) متد

زیرنویس و بالانویس را در سمت راست ایجاد می‌کند

```cpp
virtual System::SharedPtr<IMathRightSubSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSubSuperscriptOnTheRight(System::String subscript, System::String superscript)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | زیرنویس (شاخص پایین در سمت راست) |
| superscript | [System::String](../../../system/string/) | بالانویس (شاخص بالا در سمت راست) |

### مقدار بازگشت

عنصر ریاضی جدید از نوع [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)
## توضیحات



مثال: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subsuperscript = baseElement->SetSubSuperscriptOnTheRight(u"i", u"j");
```

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)
* کلاس [IMathElement](../)
* کلاس [String](../../../system/string/)
* فضای نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)