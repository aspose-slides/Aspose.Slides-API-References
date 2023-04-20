---
title: idx_set()
second_title: Aspose.Slides for C++ API Reference
description: Element of matrix
type: docs
weight: 222
url: /cpp/aspose.slides.mathtext/mathmatrix/idx_set/
---
## MathMatrix::idx_set(int32_t, int32_t, System::SharedPtr\<IMathElement\>) method


Element of matrix

```cpp
void Aspose::Slides::MathText::MathMatrix::idx_set(int32_t row, int32_t column, System::SharedPtr<IMathElement> value) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| row | **int32_t** | The zero-based index of the row to get item |
| column | **int32_t** | The zero-based index of the column to get item |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> |  |
## Remarks



Example: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->idx_set(0, 0, System::MakeObject<MathematicalText>(u"item.1.1"));
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [MathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)