---
title: Radical()
second_title: مرجع API Aspose.Slides برای C++
description: ریشه ریاضی درجهٔ داده‌شده را از آرگومان مشخص‌شده تعیین می‌کند.
type: docs
weight: 131
url: /fa/aspose.slides.mathtext/imathelement/radical/
---
## IMathElement::Radical(System::SharedPtr\<IMathElement\>) متد

ریشه ریاضی درجهٔ داده‌شده را از آرگومان مشخص‌شده تعیین می‌کند.

```cpp
virtual System::SharedPtr<IMathRadical> Aspose::Slides::MathText::IMathElement::Radical(System::SharedPtr<IMathElement> degree)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| degree | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | آرگومان Radical |

### مقدار بازگشت

نمونه جدید از نوع [IMathRadical](../../imathradical/)

## ملاحظات

مثال: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"2px");
auto degree = System::MakeObject<MathematicalText>(u"y");
auto radical = baseElement->Radical(degree);
```

## IMathElement::Radical(System::String) متد

ریشه ریاضی درجهٔ داده‌شده را از آرگومان مشخص‌شده تعیین می‌کند.

```cpp
virtual System::SharedPtr<IMathRadical> Aspose::Slides::MathText::IMathElement::Radical(System::String degree)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| degree | [System::String](../../../system/string/) | آرگومان Radical |

### مقدار بازگشت

نمونه جدید از نوع [IMathRadical](../../imathradical/)

## ملاحظات

مثال: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"2px");
auto radical = baseElement->Radical(u"3");
```

## مراجع

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathRadical](../../imathradical/)
* کلاس [IMathElement](../)
* کلاس [String](../../../system/string/)
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)