---
title: Add()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يضيف فقرة إلى نهاية المجموعة.
type: docs
weight: 27
url: /ar/aspose.slides/iparagraphcollection/add/
---
## IParagraphCollection::Add(System::SharedPtr\<IParagraph\>) طريقة


يضيف [Paragraph](../../paragraph/) إلى نهاية المجموعة.

```cpp
virtual void Aspose::Slides::IParagraphCollection::Add(System::SharedPtr<IParagraph> value)=0
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraph](../../iparagraph/)\> | [Paragraph](../../paragraph/) التي ستُضاف إلى نهاية المجموعة. |

## IParagraphCollection::Add(System::SharedPtr\<IParagraphCollection\>) طريقة


يضيف محتوى [ParagraphCollection](../../paragraphcollection/) إلى نهاية المجموعة.

```cpp
virtual int32_t Aspose::Slides::IParagraphCollection::Add(System::SharedPtr<IParagraphCollection> value)=0
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraphCollection](../)\> | [ParagraphCollection](../../paragraphcollection/) التي ستُضاف إلى نهاية المجموعة. |

### قيمة الإرجاع

المؤشر الذي تم فيه إضافة [Paragraph](../../paragraph/) أو -1 إذا لم يكن هناك ما يُضاف.

## انظر أيضا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IParagraph](../../iparagraph/)
* فئة [IParagraphCollection](../)
* مساحة اسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)