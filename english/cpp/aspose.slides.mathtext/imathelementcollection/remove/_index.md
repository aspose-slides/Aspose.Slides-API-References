---
title: Remove()
second_title: Aspose.Slides for C++ API Reference
description: Removes the first occurrence of a specific object from the collection.
type: docs
weight: 92
url: /cpp/aspose.slides.mathtext/imathelementcollection/remove/
---
## IMathElementCollection::Remove(System::SharedPtr\<IMathElement\>) method


Removes the first occurrence of a specific object from the collection.

```cpp
virtual bool Aspose::Slides::MathText::IMathElementCollection::Remove(System::SharedPtr<IMathElement> item)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | The object to remove from the collection. |

### Return Value

true if *item*  was successfully removed from the collection; otherwise, false. This method also returns false if *item*  is not found in the original collection.
## Remarks



Example: 
```cpp
auto collection = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
collection->Add(plusElement);
collection->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
collection->Remove(plusElement);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [IMathElementCollection](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)