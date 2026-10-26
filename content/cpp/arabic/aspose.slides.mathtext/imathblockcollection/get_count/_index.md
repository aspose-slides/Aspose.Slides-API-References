---
title: get_Count()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يُعيد عدد العناصر الفعلية الموجودة في المجموعة. للقراءة فقط int32_t.
type: docs
weight: 1
url: /ar/aspose.slides.mathtext/imathblockcollection/get_count/
---
## IMathBlockCollection::get_Count() طريقة

يُرجع عدد العناصر الموجودة فعليًا في المجموعة. للقراءة فقط **int32_t**.

```cpp
virtual int32_t Aspose::Slides::MathText::IMathBlockCollection::get_Count()=0
```

## ملاحظات


مثال: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
int32_t blocksCount = blockCollection->get_Count();
```

## انظر أيضًا

* الفئة [IMathBlockCollection](../)
* النطاق [Aspose::Slides::MathText](../../)
* المكتبة [Aspose.Slides](../../../)