---
title: Contains()
second_title: Aspose.Slides for C++ API Reference
description: Determines whether the collection contains a specific value.
type: docs
weight: 105
url: /aspose.slides.mathtext/mathblock/contains/
---
## MathBlock::Contains(System::SharedPtr\<IMathElement\>) method


Determines whether the collection contains a specific value.

```cpp
bool Aspose::Slides::MathText::MathBlock::Contains(System::SharedPtr<IMathElement> item) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | The object to locate in the collection. |

### Return Value

true if *item*  is found in the collection; otherwise, false.
## Remarks



Example: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
mathBlock->Add(plusElement);
mathBlock->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
bool contains = mathBlock->Contains(plusElement);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [MathBlock](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)