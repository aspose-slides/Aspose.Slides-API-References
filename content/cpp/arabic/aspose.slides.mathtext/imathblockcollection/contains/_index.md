---
title: Contains()
second_title: Aspose.Slides لـ C++ مرجع API
description: يحدد ما إذا كانت المجموعة تحتوي على قيمة معينة.
type: docs
weight: 66
url: /ar/aspose.slides.mathtext/imathblockcollection/contains/
---
## IMathBlockCollection::Contains(System::SharedPtr\<IMathBlock\>) طريقة


يحدد ما إذا كانت المجموعة تحتوي على قيمة معينة.

```cpp
virtual bool Aspose::Slides::MathText::IMathBlockCollection::Contains(System::SharedPtr<IMathBlock> item)=0
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | الكائن المراد العثور عليه في المجموعة. |

### قيمة الإرجاع

true إذا تم العثور على *item* في المجموعة؛ وإلا false.
## ملاحظات



مثال: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
blockCollection->Add(block);
bool contains = blockCollection->Contains(block);
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IMathBlock](../../imathblock/)
* فئة [IMathBlockCollection](../)
* مجال الاسم [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)