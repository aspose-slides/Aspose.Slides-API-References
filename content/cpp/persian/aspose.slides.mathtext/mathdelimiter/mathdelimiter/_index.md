---
title: MathDelimiter()
second_title: مرجع API Aspose.Slides برای C++
description: MathDelimiter را با عنصری که به عنوان آرگومان پایه تک تایی مشخص شده مقداردهی اولیه می‌کند
type: docs
weight: 144
url: /fa/aspose.slides.mathtext/mathdelimiter/mathdelimiter/
---
## MathDelimiter::MathDelimiter(System::SharedPtr\<IMathElement\>) سازنده


[MathDelimiter](../) را با عنصر مشخص شده به‌عنوان آرگومان پایهٔ تک‌تایی مقداردهی اولیه می‌کند

```cpp
Aspose::Slides::MathText::MathDelimiter::MathDelimiter(System::SharedPtr<IMathElement> element)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | عنصر پایه‌ای که جداکننده به آن اعمال می‌شود. می‌تواند مقدار null باشد. |
## ملاحظات



مثال: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = System::MakeObject<MathDelimiter>(element);
```

## همچنین ببینید

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathElement](../../imathelement/)
* کلاس [MathDelimiter](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)