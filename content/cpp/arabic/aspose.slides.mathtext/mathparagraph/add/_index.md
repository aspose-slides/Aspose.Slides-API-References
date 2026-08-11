---
title: Add()
second_title: مرجع API لـ Aspose.Slides لـ C++
description: يضيف IMathBlock إلى نهاية المجموعة.
type: docs
weight: 92
url: /ar/aspose.slides.mathtext/mathparagraph/add/
---
## MathParagraph::Add(System::SharedPtr\<IMathBlock\>) طريقة

يضيف [IMathBlock](../../imathblock/) إلى نهاية المجموعة.

```cpp
void Aspose::Slides::MathText::MathParagraph::Add(System::SharedPtr<IMathBlock> mathBlock) override
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| mathBlock | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | كتلة رياضية سيتم إضافتها إلى نهاية المجموعة |
## ملاحظات

مثال:
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x")));
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IMathBlock](../../imathblock/)
* فئة [MathParagraph](../)
* نطاق [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)