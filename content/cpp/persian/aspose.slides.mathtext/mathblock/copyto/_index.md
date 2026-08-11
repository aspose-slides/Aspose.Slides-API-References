---
title: CopyTo()
second_title: مرجع API Aspose.Slides برای C++
description: به آرایهٔ مشخص شده کپی می‌کند.
type: docs
weight: 118
url: /fa/aspose.slides.mathtext/mathblock/copyto/
---
## MathBlock::CopyTo(System::ArrayPtr\<System::SharedPtr\<IMathElement\>\>, int32_t) متد

به آرایهٔ مشخص شده کپی می‌کند.

```cpp
void Aspose::Slides::MathText::MathBlock::CopyTo(System::ArrayPtr<System::SharedPtr<IMathElement>> array, int32_t arrayIndex) override
```

### آرگومان‌ها

| پارامتر | نوع | شرح |
| --- | --- | --- |
| array | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\>\> | آرایه‌ای که به آن کپی می‌شود. |
| arrayIndex | **int32_t** | شاخصی که از آن شروع به کپی می‌کند. |
## توضیحات



مثال: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
mathBlock->Add(plusElement);
mathBlock->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
auto destinationArray = System::MakeArray<System::SharedPtr<IMathElement>>(mathBlock->get_Count());
mathBlock->CopyTo(destinationArray, 0);
```

## موارد مرتبط

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathElement](../../imathelement/)
* کلاس [MathBlock](../)
* فضای نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)