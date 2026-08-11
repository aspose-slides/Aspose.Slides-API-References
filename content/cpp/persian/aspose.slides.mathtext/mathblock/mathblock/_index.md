---
title: MathBlock()
second_title: مرجع API Aspose.Slides برای C++
description: یک نمونه جدید از کلاس MathBlock را مقداردهی می‌کند.
type: docs
weight: 66
url: /fa/aspose.slides.mathtext/mathblock/mathblock/
---
## MathBlock::MathBlock() سازنده

یک نمونه جدید از کلاس [MathBlock](../) را مقداردهی می‌کند.

```cpp
Aspose::Slides::MathText::MathBlock::MathBlock()
```

## ملاحظات

مثال: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>();
```

## MathBlock::MathBlock(System::SharedPtr\<IMathElement\>) سازنده

یک بلوک ریاضی جدید ایجاد می‌کند و عنصر مشخص‌شده را در آن قرار می‌دهد

```cpp
Aspose::Slides::MathText::MathBlock::MathBlock(System::SharedPtr<IMathElement> mathElement)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | عنصر ریاضی که در بلوک قرار می‌گیرد |
## ملاحظات

مثال: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
```

## MathBlock::MathBlock(System::SharedPtr\<System::Collections::Generic::IEnumerable\<System::SharedPtr\<IMathElement\>\>\>) سازنده

یک بلوک ریاضی جدید ایجاد می‌کند و عناصر مشخص‌شده را در آن قرار می‌دهد

```cpp
Aspose::Slides::MathText::MathBlock::MathBlock(System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<IMathElement>>> mathElements)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| mathElements | [System::SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\>\>\> | عناصر ریاضی که در بلوک قرار می‌گیرند |
## ملاحظات

مثال: 
```cpp
auto elems = System::MakeArray<System::SharedPtr<IMathElement>>({System::MakeObject<MathematicalText>(u"item1"), System::MakeObject<MathematicalText>(u"item2")});
auto mathBlock = System::MakeObject<MathBlock>(elems);
```

## مراجع

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [MathBlock](../)
* کلاس [IMathElement](../../imathelement/)
* کلاس [IEnumerable](../../../system.collections.generic/ienumerable/)
* فضای نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)