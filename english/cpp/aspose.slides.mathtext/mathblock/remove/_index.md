---
title: Remove()
second_title: Aspose.Slides for C++ API Reference
description: Removes the first occurrence of a specific object from the collection.
type: docs
weight: 131
url: /cpp/aspose.slides.mathtext/mathblock/remove/
---
## MathBlock::Remove([System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\>) method


Removes the first occurrence of a specific object from the collection.

```cpp
bool Aspose::Slides::MathText::MathBlock::Remove(System::SharedPtr<IMathElement> item) override
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
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
mathBlock->Add(plusElement);
mathBlock->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
mathBlock->Remove(plusElement);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [MathBlock](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
