---
title: idx_get()
second_title: مرجع واجهة برمجة التطبيقات Aspose.Slides للغة C++
description: يحصل على العنصر بالفهرس المحدد. للقراءة فقط IMathBlock.
type: docs
weight: 40
url: /ar/aspose.slides.mathtext/mathparagraph/idx_get/
---
## MathParagraph::idx_get(int32_t) طريقة

يحصل على العنصر في الفهرس المحدد. للقراءة فقط [IMathBlock](../../imathblock/).

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathParagraph::idx_get(int32_t index) override
```


### معاملات

| معامل | نوع | وصف |
| --- | --- | --- |
| index | **int32_t** | المؤشر الصفري للعنصر المراد الحصول عليه |

### قيمة الإرجاع

كتلة من نص رياضي.

## ملاحظات



مثال: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
auto block = mathParagraph->idx_get(1);
```

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IMathBlock](../../imathblock/)
* فئة [MathParagraph](../)
* مساحة الأسماء [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)