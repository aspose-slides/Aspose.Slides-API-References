---
title: Remove()
second_title: Aspose.Slides لمرجع API C++
description: يزيل الظهور الأول لكائن معين من ICollection.
type: docs
weight: 131
url: /ar/aspose.slides/paragraphcollection/remove/
---
## ParagraphCollection::Remove(System::SharedPtr\<IParagraph\>) طريقة

يزيل الظهور الأول لكائن معين من [ICollection](../../../system.collections.generic/icollection/).

```cpp
bool Aspose::Slides::ParagraphCollection::Remove(System::SharedPtr<IParagraph> item) override
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraph](../../iparagraph/)\> | الكائن الذي سيتم إزالته من [ICollection](../../../system.collections.generic/icollection/). |

### قيمة الإرجاع

صحيح إذا تم إزالة *item* بنجاح من [ICollection](../../../system.collections.generic/icollection/)؛ وإلا، false. تُعيد هذه الطريقة false أيضًا إذا لم يُعثر على *item* في [ICollection](../../../system.collections.generic/icollection/) الأصلي.

## أنظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IParagraph](../../iparagraph/)
* Class [ParagraphCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)