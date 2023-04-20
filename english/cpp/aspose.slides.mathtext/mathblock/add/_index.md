---
title: Add()
second_title: Aspose.Slides for C++ API Reference
description: Adds a math element to the end of the collection.
type: docs
weight: 79
url: /cpp/aspose.slides.mathtext/mathblock/add/
---
## MathBlock::Add(System::SharedPtr\<IMathElement\>) method


Adds a math element to the end of the collection.

```cpp
void Aspose::Slides::MathText::MathBlock::Add(System::SharedPtr<IMathElement> item) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | The [IMathElement](../../imathelement/) to be added to the end of the collection. |
## Remarks



Example: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
mathBlock->Add(System::MakeObject<MathematicalText>(u"+"));
mathBlock->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [MathBlock](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)