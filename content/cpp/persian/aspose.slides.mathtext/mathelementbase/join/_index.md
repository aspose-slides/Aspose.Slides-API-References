---
title: Join()
second_title: Aspose.Slides برای C++ مرجع API
description: یک عنصر ریاضی را به هم می‌پیوندد و یک بلوک ریاضی تشکیل می‌دهد
type: docs
weight: 1
url: /fa/aspose.slides.mathtext/mathelementbase/join/
---
## MathElementBase::Join(System::SharedPtr\<IMathElement\>) متد

یک عنصر ریاضی را به هم می‌پیوندد و یک بلوک ریاضی تشکیل می‌دهد

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathElementBase::Join(System::SharedPtr<IMathElement> mathElement) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | عنصری که باید به هم پیوست شود |

### مقدار بازگشت

یک [IMathBlock](../../imathblock/) جدید که حاوی این نمونه و آرگومان مشخص‌شده است
## توضیحات



مثال: 
```cpp
auto element1 = System::MakeObject<MathematicalText>(u"x");
auto element2 = System::MakeObject<MathematicalText>(u"y");
auto block = element1->Join(element2);
```

## MathElementBase::Join(System::String) متد

یک متن ریاضی را به هم می‌پیوندد و یک بلوک ریاضی تشکیل می‌دهد

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathElementBase::Join(System::String mathText) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | متنی ریاضی که باید به هم پیوست شود |

### مقدار بازگشت

یک [IMathBlock](../../imathblock/) جدید که حاوی این نمونه و آرگومان مشخص‌شده است
## توضیحات



مثال: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto block = element->Join(u"+y");
```

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathBlock](../../imathblock/)
* کلاس [IMathElement](../../imathelement/)
* کلاس [MathElementBase](../)
* کلاس [String](../../../system/string/)
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)