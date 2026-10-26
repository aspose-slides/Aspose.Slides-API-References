---
title: Insert()
second_title: مرجع واجهة برمجة تطبيقات Aspose.Slides للـ C++
description: يقوم بإدراج IMathBlock في المجموعة عند الفهرس المحدد.
type: docs
weight: 27
url: /ar/aspose.slides.mathtext/imathblockcollection/insert/
---
## IMathBlockCollection::Insert(int32_t, System::SharedPtr\<IMathBlock\>) طريقة

يقوم بإدراج [IMathBlock](../../imathblock/) في المجموعة عند الفهرس المحدد.

```cpp
virtual void Aspose::Slides::MathText::IMathBlockCollection::Insert(int32_t index, System::SharedPtr<IMathBlock> item)=0
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | **int32_t** | المؤشر الصفري الذي يجب إدراج العنصر عنده. |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | ال[IMathBlock](../../imathblock/) لإدراجه. |

## ملاحظات

مثال:
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
blockCollection->Insert(0, block);
```

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* الصنف [IMathBlock](../../imathblock/)
* الصنف [IMathBlockCollection](../)
* النطاق [Aspose::Slides::MathText](../../)
* المكتبة [Aspose.Slides](../../../)