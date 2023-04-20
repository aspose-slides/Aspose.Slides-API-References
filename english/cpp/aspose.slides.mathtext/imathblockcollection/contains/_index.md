---
title: Contains()
second_title: Aspose.Slides for C++ API Reference
description: Determines whether the collection contains a specific value.
type: docs
weight: 66
url: /cpp/aspose.slides.mathtext/imathblockcollection/contains/
---
## IMathBlockCollection::Contains(System::SharedPtr\<IMathBlock\>) method


Determines whether the collection contains a specific value.

```cpp
virtual bool Aspose::Slides::MathText::IMathBlockCollection::Contains(System::SharedPtr<IMathBlock> item)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | The object to locate in the collection. |

### Return Value

true if *item*  is found in the collection; otherwise, false.
## Remarks



Example: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
blockCollection->Add(block);
bool contains = blockCollection->Contains(block);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathBlock](../../imathblock/)
* Class [IMathBlockCollection](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)