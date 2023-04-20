---
title: IndexOf()
second_title: Aspose.Slides for C++ API Reference
description: Determines the index of a specific IMathBlock in collection.
type: docs
weight: 79
url: /cpp/aspose.slides.mathtext/imathblockcollection/indexof/
---
## IMathBlockCollection::IndexOf(System::SharedPtr\<IMathBlock\>) method


Determines the index of a specific [IMathBlock](../../imathblock/) in collection.

```cpp
virtual int32_t Aspose::Slides::MathText::IMathBlockCollection::IndexOf(System::SharedPtr<IMathBlock> item)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | The item to locate in the collection. |

### Return Value

The index of *item*  if found in the collection; otherwise, -1.
## Remarks



Example: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
blockCollection->Add(block);
int32_t index = blockCollection->IndexOf(block);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathBlock](../../imathblock/)
* Class [IMathBlockCollection](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)