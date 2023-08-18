---
title: RemoveAt()
second_title: Aspose.Slides for C++ API Reference
description: Removes the element at the specified index of the collection.
type: docs
weight: 170
url: /aspose.slides.mathtext/mathblock/removeat/
---
## MathBlock::RemoveAt(int32_t) method


Removes the element at the specified index of the collection.

```cpp
void Aspose::Slides::MathText::MathBlock::RemoveAt(int32_t index) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | The zero-based index of the element to remove. |
## Remarks



Example: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
mathBlock->Add(plusElement);
mathBlock->Insert(0, System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
mathBlock->RemoveAt(2);
```

## See Also

* Class [MathBlock](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)