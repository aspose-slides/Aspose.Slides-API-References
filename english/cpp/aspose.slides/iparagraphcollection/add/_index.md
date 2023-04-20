---
title: Add()
second_title: Aspose.Slides for C++ API Reference
description: Adds a Paragraph to the end of collection.
type: docs
weight: 27
url: /cpp/aspose.slides/iparagraphcollection/add/
---
## IParagraphCollection::Add(System::SharedPtr\<IParagraph\>) method


Adds a [Paragraph](../../paragraph/) to the end of collection.

```cpp
virtual void Aspose::Slides::IParagraphCollection::Add(System::SharedPtr<IParagraph> value)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraph](../../iparagraph/)\> | The [Paragraph](../../paragraph/) to be added to the end of the collection. |

## IParagraphCollection::Add(System::SharedPtr\<IParagraphCollection\>) method


Adds a content of [ParagraphCollection](../../paragraphcollection/) to the end of collection.

```cpp
virtual int32_t Aspose::Slides::IParagraphCollection::Add(System::SharedPtr<IParagraphCollection> value)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraphCollection](../)\> | The [ParagraphCollection](../../paragraphcollection/) to be added to the end of the collection. |

### Return Value

The index at which the [Paragraph](../../paragraph/) has been added or -1 if there are nothing to add.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IParagraph](../../iparagraph/)
* Class [IParagraphCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)