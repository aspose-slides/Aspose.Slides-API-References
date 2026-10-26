---
title: MathArray()
second_title: مرجع API Aspose.Slides برای C++
description: یک آرایه ریاضی ایجاد می‌کند و عنصر مشخص‌شده را در آن قرار می‌دهد
type: docs
weight: 144
url: /fa/aspose.slides.mathtext/matharray/matharray/
---
## MathArray::MathArray(System::SharedPtr\<IMathElement\>) سازنده

یک آرایه ریاضی ایجاد می‌کند و عنصر مشخص‌شده را در آن قرار می‌دهد

```cpp
Aspose::Slides::MathText::MathArray::MathArray(System::SharedPtr<IMathElement> element)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | عنصری که باید در آرایه قرار گیرد |
## توضیحات

مثال:
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
```

## MathArray::MathArray(System::SharedPtr\<System::Collections::Generic::IEnumerable\<System::SharedPtr\<IMathElement\>\>\>) سازنده

یک آرایه ریاضی ایجاد می‌کند و عناصر مشخص‌شده را در آن قرار می‌دهد

```cpp
Aspose::Slides::MathText::MathArray::MathArray(System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<IMathElement>>> elements)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| elements | [System::SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\>\>\> | عناصری که باید در آرایه قرار گیرند |

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathElement](../../imathelement/)
* کلاس [MathArray](../)
* کلاس [IEnumerable](../../../system.collections.generic/ienumerable/)
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)