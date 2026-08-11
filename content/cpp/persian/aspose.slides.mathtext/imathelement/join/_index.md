---
title: Join()
second_title: Aspose.Slides برای C++ مرجع API
description: یک عنصر ریاضی را می‌پیوندد و یک بلوک ریاضی ایجاد می‌کند
type: docs
weight: 14
url: /fa/aspose.slides.mathtext/imathelement/join/
---
## IMathElement::Join(System::SharedPtr\<IMathElement\>) متد

یک عنصر ریاضی را می‌پیوندد و یک بلوک ریاضی تشکیل می‌دهد

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathElement::Join(System::SharedPtr<IMathElement> mathElement)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | عنصری که باید پیوست شود |

### مقدار بازگشت

یک [IMathBlock](../../imathblock/) جدید که این نمونه و آرگومان مشخص‌شده را شامل می‌شود
## ملاحظات



مثال: 
```cpp
auto element1 = System::MakeObject<MathematicalText>(u"x");
auto element2 = System::MakeObject<MathematicalText>(u"y");
auto block = element1->Join(element2);
```

## IMathElement::Join(System::String) متد

یک متن ریاضی را می‌پیوندد و یک بلوک ریاضی تشکیل می‌دهد

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathElement::Join(System::String mathText)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | متن ریاضی که باید پیوست شود |

### مقدار بازگشت

یک [IMathBlock](../../imathblock/) جدید که این نمونه و آرگومان مشخص‌شده را شامل می‌شود
## ملاحظات



مثال: 
```cpp
System::SharedPtr<IMathElement> element = System::MakeObject<MathematicalText>(u"x");
auto block = element->Join(u"+y");
```

## مراجع

* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathBlock](../../imathblock/)
* کلاس [IMathElement](../)
* کلاس [String](../../../system/string/)
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)