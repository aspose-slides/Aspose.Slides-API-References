---
title: Remove()
second_title: Aspose.Slides for C++ API Reference
description: Removes the first occurrence of a specific object from the collection/>.
type: docs
weight: 40
url: /cpp/aspose.slides.mathtext/imathblockcollection/remove/
---
## IMathBlockCollection::Remove([System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\>) method


Removes the first occurrence of a specific object from the collection/>.

```cpp
virtual bool Aspose::Slides::MathText::IMathBlockCollection::Remove(System::SharedPtr<IMathBlock> item)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | The object to remove from the collection. |

### Return Value

true if *item*  was successfully removed from the collection; otherwise, false. This method also returns false if *item*  is not found in the original collection/>.
## Remarks



Example: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
blockCollection->Add(block);
blockCollection->Remove(block);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathBlock](../../imathblock/)
* Class [IMathBlockCollection](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
