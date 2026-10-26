---
title: Radical()
second_title: مرجع API Aspose.Slides برای C++
description: ریشه ریاضی را برای درجهٔ داده‌شده از آرگومان مشخص‌شده تعیین می‌کند.
type: docs
weight: 118
url: /fa/aspose.slides.mathtext/mathelementbase/radical/
---
## MathElementBase::Radical(System::SharedPtr\<IMathElement\>) متد

ریشه ریاضی را برای درجهٔ داده‌شده از آرگومان مشخص‌شده تعیین می‌کند.

```cpp
System::SharedPtr<IMathRadical> Aspose::Slides::MathText::MathElementBase::Radical(System::SharedPtr<IMathElement> degree) override
```

### Arguments

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| degree | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | آرگومان Radical |

### Return Value

نمونهٔ جدیدی از نوع [IMathRadical](../../imathradical/)

## Remarks

مثال: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"2px");
auto degree = System::MakeObject<MathematicalText>(u"y");
auto radical = baseElement->Radical(degree);
```

## MathElementBase::Radical(System::String) متد

ریشه ریاضی را برای درجهٔ داده‌شده از آرگومان مشخص‌شده تعیین می‌کند.

```cpp
System::SharedPtr<IMathRadical> Aspose::Slides::MathText::MathElementBase::Radical(System::String degree) override
```

### Arguments

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| degree | [System::String](../../../system/string/) | آرگومان Radical |

### Return Value

نمونهٔ جدیدی از نوع [IMathRadical](../../imathradical/)

## Remarks

مثال: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"2px");
auto radical = baseElement->Radical(u"3");
```

## همچنین ببینید

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathRadical](../../imathradical/)
* کلاس [IMathElement](../../imathelement/)
* کلاس [MathElementBase](../)
* کلاس [String](../../../system/string/)
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)