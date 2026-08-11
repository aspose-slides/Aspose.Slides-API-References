---
title: Insert()
second_title: مرجع API Aspose.Slides برای C++
description: IMathBlock را در مجموعه در اندیس مشخص شده درج می‌کند.
type: docs
weight: 144
url: /fa/aspose.slides.mathtext/mathparagraph/insert/
---
## MathParagraph::Insert(int32_t, System::SharedPtr\<IMathBlock\>) متد

[IMathBlock](../../imathblock/) را در مجموعه در اندیس مشخص شده درج می‌کند.

```cpp
void Aspose::Slides::MathText::MathParagraph::Insert(int32_t index, System::SharedPtr<IMathBlock> mathBlock) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | **int32_t** | اندیس صفر مبنا که یک مورد باید در آن درج شود. |
| mathBlock | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | [IMathBlock](../../imathblock/) برای درج. |
## توضیحات



مثال: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
mathParagraph->Insert(0, block);
```

## موارد مرتبط

* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathBlock](../../imathblock/)
* کلاس [MathParagraph](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)