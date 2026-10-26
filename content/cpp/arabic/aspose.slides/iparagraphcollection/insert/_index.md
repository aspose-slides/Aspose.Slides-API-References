---
title: Insert()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يدرج Paragraph في المجموعة عند الفهرس المحدد.
type: docs
weight: 40
url: /ar/aspose.slides/iparagraphcollection/insert/
---
## IParagraphCollection::Insert(int32_t, System::SharedPtr\<IParagraph\>) طريقة


يدرج [Paragraph](../../paragraph/) في المجموعة في الفهرس المحدد.

```cpp
virtual void Aspose::Slides::IParagraphCollection::Insert(int32_t index, System::SharedPtr<IParagraph> value)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | الفهرس الصفري الذي يجب فيه إدراج [Paragraph](../../paragraph/). |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraph](../../iparagraph/)\> | [Paragraph](../../paragraph/) للإدراج. |

## IParagraphCollection::Insert(int32_t, System::SharedPtr\<IParagraphCollection\>) طريقة


يدرج محتوى [ParagraphCollection](../../paragraphcollection/) في المجموعة في الفهرس المحدد.

```cpp
virtual void Aspose::Slides::IParagraphCollection::Insert(int32_t index, System::SharedPtr<IParagraphCollection> value)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | الفهرس الصفري الذي يجب فيه إدراج الفقرات. |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraphCollection](../)\> | الفقرات المراد إدراجها. |

## See Also

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IParagraph](../../iparagraph/)
* فئة [IParagraphCollection](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)