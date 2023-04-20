---
title: idx_set()
second_title: Aspose.Slides for C++ API Reference
description: Sets IMathElement at the specified index.
type: docs
weight: 40
url: /cpp/aspose.slides.mathtext/mathblock/idx_set/
---
## MathBlock::idx_set(int32_t, System::SharedPtr\<IMathElement\>) method


Sets [IMathElement](../../imathelement/) at the specified index.

```cpp
void Aspose::Slides::MathText::MathBlock::idx_set(int32_t index, System::SharedPtr<IMathElement> value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | The zero-based index of the item |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | The mathematical element. |
## Remarks



Example: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto firstElem = mathBlock->idx_get(0);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [MathBlock](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)