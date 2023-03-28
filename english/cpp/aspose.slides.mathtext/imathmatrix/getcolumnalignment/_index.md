---
title: GetColumnAlignment()
second_title: Aspose.Slides for C++ API Reference
description: Get the horizontal alignment of the specified column
type: docs
weight: 235
url: /cpp/aspose.slides.mathtext/imathmatrix/getcolumnalignment/
---
## IMathMatrix::GetColumnAlignment(**int32_t**) method


Get the horizontal alignment of the specified column

```cpp
virtual MathHorizontalAlignment Aspose::Slides::MathText::IMathMatrix::GetColumnAlignment(int32_t columnIndex)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| columnIndex | **int32_t** | Zero-based column index |

### Return Value

Horizontal Alignment of specified column
## Remarks



Example: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
auto alignment = matrix->GetColumnAlignment(0);
```

## See Also

* Enum [MathHorizontalAlignment](../../mathhorizontalalignment/)
* Class [IMathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
