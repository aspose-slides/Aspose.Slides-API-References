---
title: get_Count()
second_title: مرجع API Aspose.Slides للغة C++
description: يُعيد عدد عناصر الرياضيات الفرعية الموجودة فعليًا في المجموعة. للقراءة فقط int32_t.
type: docs
weight: 1
url: /ar/aspose.slides.mathtext/mathblock/get_count/
---
## MathBlock::get_Count() طريقة

Gets the number of child math elements actually contained in the collection. للقراءة فقط **int32_t**.

```cpp
int32_t Aspose::Slides::MathText::MathBlock::get_Count() override
```

## ملاحظات


مثال: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
int32_t count = mathBlock->get_Count();
```

## انظر أيضًا

* الفئة [MathBlock](../)
* النطاق [Aspose::Slides::MathText](../../)
* المكتبة [Aspose.Slides](../../../)