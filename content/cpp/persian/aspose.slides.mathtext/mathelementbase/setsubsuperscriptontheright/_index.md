---
title: SetSubSuperscriptOnTheRight()
second_title: مرجع API Aspose.Slides برای C++
description: زیرنویس و بالانویس را در سمت راست ایجاد می‌کند
type: docs
weight: 92
url: /fa/aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright/
---
## MathElementBase::SetSubSuperscriptOnTheRight(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) متد


زیرنویس و بالانویس را در سمت راست ایجاد می‌کند

```cpp
System::SharedPtr<IMathRightSubSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubSuperscriptOnTheRight(System::SharedPtr<IMathElement> subscript, System::SharedPtr<IMathElement> superscript) override
```


### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | زیرنویس (اندیس پایین سمت راست) |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | بالانویس (اندیس بالا سمت راست) |

### مقدار بازگشتی

عنصر ریاضی جدید از نوع [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)
## نکات



مثال: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto subsuperscript = baseElement->SetSubSuperscriptOnTheRight(subscript, superscript);
```

## MathElementBase::SetSubSuperscriptOnTheRight(System::String, System::String) متد


زیرنویس و بالانویس را در سمت راست ایجاد می‌کند

```cpp
System::SharedPtr<IMathRightSubSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubSuperscriptOnTheRight(System::String subscript, System::String superscript) override
```


### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | زیرنویس (اندیس پایین سمت راست) |
| superscript | [System::String](../../../system/string/) | بالانویس (اندیس بالا سمت راست) |

### مقدار بازگشتی

عنصر ریاضی جدید از نوع [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)
## نکات



مثال: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subsuperscript = baseElement->SetSubSuperscriptOnTheRight(u"i", u"j");
```

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)
* کلاس [IMathElement](../../imathelement/)
* کلاس [MathElementBase](../)
* کلاس [String](../../../system/string/)
* فضای نام [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)