---
title: Insert()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يُدرج IMathBlock في المجموعة عند الفهرس المحدد.
type: docs
weight: 144
url: /ar/aspose.slides.mathtext/mathparagraph/insert/
---
## MathParagraph::Insert(int32_t, System::SharedPtr\<IMathBlock\>) طريقة

يُدرج [IMathBlock](../../imathblock/) في المجموعة عند الفهرس المحدد.

```cpp
void Aspose::Slides::MathText::MathParagraph::Insert(int32_t index, System::SharedPtr<IMathBlock> mathBlock) override
```

### المعلمات

| المُعامل | النوع | الوصف |
| --- | --- | --- |
| index | **int32_t** | المؤشر الصفري الذي يجب أن يُدرج العنصر عنده. |
| mathBlock | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | الـ [IMathBlock](../../imathblock/) لإدراجه. |

## ملاحظات


مثال: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
mathParagraph->Insert(0, block);
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IMathBlock](../../imathblock/)
* فئة [MathParagraph](../)
* نطاق الاسم [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)