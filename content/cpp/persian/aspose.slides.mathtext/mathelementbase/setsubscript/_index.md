---
title: SetSubscript()
second_title: مرجع API Aspose.Slides برای C++
description: ایجاد زیرنویس
type: docs
weight: 66
url: /fa/aspose.slides.mathtext/mathelementbase/setsubscript/
---
## MathElementBase::SetSubscript(System::SharedPtr\<IMathElement\>) متد

ایجاد زیرنویس

```cpp
System::SharedPtr<IMathSubscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubscript(System::SharedPtr<IMathElement> subscript) override
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | زیرنویس (شاخص پایین در سمت راست) |

### مقدار بازگشتی

عنصر ریاضی جدید از نوع [IMathSubscriptElement](../../imathsubscriptelement/)
## توضیحات

مثال: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto index = System::MakeObject<MathematicalText>(u"i");
auto subscript = element->SetSubscript(index);
```

## MathElementBase::SetSubscript(System::String) متد

ایجاد زیرنویس

```cpp
System::SharedPtr<IMathSubscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubscript(System::String subscript) override
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | زیرنویس (شاخص پایین در سمت راست) |

### مقدار بازگشتی

عنصر ریاضی جدید از نوع [IMathSubscriptElement](../../imathsubscriptelement/)
## توضیحات

مثال: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto subscript = element->SetSubscript(u"i");
```

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathSubscriptElement](../../imathsubscriptelement/)
* Class [IMathElement](../../imathelement/)
* Class [MathElementBase](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)