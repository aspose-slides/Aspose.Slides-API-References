---
title: Insert()
second_title: Aspose.Slides for C++ API Reference
description: Inserts a MathElement into the collection at the specified index.
type: docs
weight: 157
url: /aspose.slides.mathtext/mathblock/insert/
---
## MathBlock::Insert(int32_t, System::SharedPtr\<IMathElement\>) method


Inserts a MathElement into the collection at the specified index.

```cpp
void Aspose::Slides::MathText::MathBlock::Insert(int32_t index, System::SharedPtr<IMathElement> item) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | The zero-based index at which MathElement should be inserted. |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | The MathElement to insert. |
## Remarks



Example: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
mathBlock->Add(plusElement);
mathBlock->Insert(0, System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [MathBlock](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)