---
title: SetSubscript()
second_title: Aspose.Slides برای C++ مرجع API
description: زیرنویس ایجاد می‌کند
type: docs
weight: 79
url: /fa/aspose.slides.mathtext/imathelement/setsubscript/
---
## IMathElement::SetSubscript(System::SharedPtr\<IMathElement\>) متد

زیرنویس ایجاد می‌کند

```cpp
virtual System::SharedPtr<IMathSubscriptElement> Aspose::Slides::MathText::IMathElement::SetSubscript(System::SharedPtr<IMathElement> subscript)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | زیرنویس (شاخص پایین در سمت راست) |

### مقدار بازگشتی

عنصر ریاضی جدید از نوع [IMathSubscriptElement](../../imathsubscriptelement/)

## نکات



مثال:
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto index = System::MakeObject<MathematicalText>(u"i");
auto subscript = element->SetSubscript(index);
```

## IMathElement::SetSubscript(System::String) متد

زیرنویس ایجاد می‌کند

```cpp
virtual System::SharedPtr<IMathSubscriptElement> Aspose::Slides::MathText::IMathElement::SetSubscript(System::String subscript)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | زیرنویس (شاخص پایین در سمت راست) |

### مقدار بازگشتی

عنصر ریاضی جدید از نوع [IMathSubscriptElement](../../imathsubscriptelement/)

## نکات



مثال:
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto subscript = element->SetSubscript(u"i");
```

## مراجعه کنید

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathSubscriptElement](../../imathsubscriptelement/)
* کلاس [IMathElement](../)
* کلاس [String](../../../system/string/)
* فضای نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)