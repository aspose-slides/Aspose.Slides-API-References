---
title: idx_get()
second_title: Aspose.Slides for C++ API Reference
description: Gets IMathElement at the specified index.
type: docs
weight: 27
url: /cpp/aspose.slides.mathtext/mathblock/idx_get/
---
## MathBlock::idx_get(**int32_t**) method


Gets [IMathElement](../../imathelement/) at the specified index.

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathBlock::idx_get(int32_t index) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | The zero-based index of the item |

### Return Value

The mathematical element.
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
