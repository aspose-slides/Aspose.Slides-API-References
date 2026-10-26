---
title: SetSuperscript()
second_title: Aspose.Slides برای مرجع API C++
description: بالانویس ایجاد می‌کند
type: docs
weight: 92
url: /fa/aspose.slides.mathtext/imathelement/setsuperscript/
---
## IMathElement::SetSuperscript(System::SharedPtr\<IMathElement\>) متد

یک بالانویس ایجاد می‌کند

```cpp
virtual System::SharedPtr<IMathSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSuperscript(System::SharedPtr<IMathElement> superscript)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | بالانویس (شاخص بالایی در سمت راست) |

### مقدار بازگشت

عنصر ریاضی جدید از نوع [IMathSuperscriptElement](../../imathsuperscriptelement/)

## توضیحات

مثال: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto index = System::MakeObject<MathematicalText>(u"4");
auto superscript = element->SetSuperscript(index);
```

## IMathElement::SetSuperscript(System::String) متد

یک بالانویس ایجاد می‌کند

```cpp
virtual System::SharedPtr<IMathSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSuperscript(System::String superscript)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| superscript | [System::String](../../../system/string/) | بالانویس (شاخص بالایی در سمت راست) |

### مقدار بازگشت

عنصر ریاضی جدید از نوع [IMathSuperscriptElement](../../imathsuperscriptelement/)

## توضیحات

مثال: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto superscript = element->SetSuperscript(u"4");
```

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathSuperscriptElement](../../imathsuperscriptelement/)
* کلاس [IMathElement](../)
* کلاس [String](../../../system/string/)
* فضای نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)