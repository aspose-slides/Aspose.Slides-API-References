---
title: Remove()
second_title: Aspose.Slides لـ C++ مرجع API
description: يزيل الظهور الأول لكائن محدد من المجموعة/>.
type: docs
weight: 40
url: /ar/aspose.slides.mathtext/imathblockcollection/remove/
---
## IMathBlockCollection::Remove(System::SharedPtr\<IMathBlock\>) طريقة


يزيل الظهور الأول لكائن معين من المجموعة/>

```cpp
virtual bool Aspose::Slides::MathText::IMathBlockCollection::Remove(System::SharedPtr<IMathBlock> item)=0
```


### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | الكائن لإزالته من المجموعة. |

### قيمة الإرجاع

true إذا تم إزالة *item* بنجاح من المجموعة؛ وإلا، false. تعيد هذه الطريقة أيضًا false إذا لم يتم العثور على *item* في المجموعة الأصلية/>

## ملاحظات



مثال:
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
blockCollection->Add(block);
blockCollection->Remove(block);
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IMathBlock](../../imathblock/)
* فئة [IMathBlockCollection](../)
* مساحة أسماء [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)