---
title: Add()
second_title: مرجع API Aspose.Slides برای C++
description: IMathBlock را به انتهای مجموعه اضافه می‌کند.
type: docs
weight: 92
url: /fa/aspose.slides.mathtext/mathparagraph/add/
---
## MathParagraph::Add(System::SharedPtr\<IMathBlock\>) متد


[IMathBlock](../../imathblock/) را به انتهای مجموعه اضافه می‌کند.

```cpp
void Aspose::Slides::MathText::MathParagraph::Add(System::SharedPtr<IMathBlock> mathBlock) override
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| mathBlock | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | یک بلوک ریاضی که به انتهای مجموعه اضافه خواهد شد |
## توضیحات



مثال: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x")));
```

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathBlock](../../imathblock/)
* کلاس [MathParagraph](../)
* فضای نام [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)