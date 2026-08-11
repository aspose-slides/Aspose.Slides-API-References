---
title: Remove()
second_title: مرجع API Aspose.Slides للـ C++
description: يزيل الظهور الأول لكائن محدد من المجموعة/>
type: docs
weight: 105
url: /ar/aspose.slides.mathtext/mathparagraph/remove/
---
## MathParagraph::Remove(System::SharedPtr\<IMathBlock\>) طريقة


يزيل الظهور الأول لكائن محدد من المجموعة/> 

```cpp
bool Aspose::Slides::MathText::MathParagraph::Remove(System::SharedPtr<IMathBlock> mathBlock) override
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| mathBlock | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | الكائن المراد إزالته من المجموعة. |

### قيمة الإرجاع

صحيح إذا تم إزالة *mathBlock* بنجاح من المجموعة؛ وإلا، خطأ. كما تعيد هذه الطريقة خطأ إذا لم يتم العثور على *mathBlock* في المجموعة الأصلية/>.

## ملاحظات



مثال: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x")));
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
mathParagraph->Add(block);
mathParagraph->Remove(block);
```

## انظر أيضاً

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IMathBlock](../../imathblock/)
* فئة [MathParagraph](../)
* مساحة الأسماء [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)