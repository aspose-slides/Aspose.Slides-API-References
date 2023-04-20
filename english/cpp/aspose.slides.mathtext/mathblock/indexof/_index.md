---
title: IndexOf()
second_title: Aspose.Slides for C++ API Reference
description: Determines the index of a specific math element in collection.
type: docs
weight: 144
url: /cpp/aspose.slides.mathtext/mathblock/indexof/
---
## MathBlock::IndexOf(System::SharedPtr\<IMathElement\>) method


Determines the index of a specific math element in collection.

```cpp
int32_t Aspose::Slides::MathText::MathBlock::IndexOf(System::SharedPtr<IMathElement> item) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | The element to locate in the collection. |

### Return Value

The index of *item*  if found in the collection; otherwise, -1.
## Remarks



Example: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
mathBlock->Add(plusElement);
mathBlock->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
int32_t index = mathBlock->IndexOf(plusElement);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [MathBlock](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)