---
title: idx_get()
second_title: Aspose.Slides for C++ API Reference
description: Elements of matrix
type: docs
weight: 209
url: /cpp/aspose.slides.mathtext/imathmatrix/idx_get/
---
## IMathMatrix::idx_get(int32_t, int32_t) method


Elements of matrix

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathMatrix::idx_get(int32_t row, int32_t column)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| row | **int32_t** | The zero-based index of the row to get item |
| column | **int32_t** | The zero-based index of the column to get item |

### Return Value


## Remarks



Example: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->idx_set(0, 0, System::MakeObject<MathematicalText>(u"item.1.1"));
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [IMathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)