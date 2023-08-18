---
title: SetColumnAlignment()
second_title: Aspose.Slides for C++ API Reference
description: Set the horizontal alignment of the specified column
type: docs
weight: 261
url: /aspose.slides.mathtext/mathmatrix/setcolumnalignment/
---
## MathMatrix::SetColumnAlignment(int32_t, MathHorizontalAlignment) method


Set the horizontal alignment of the specified column

```cpp
void Aspose::Slides::MathText::MathMatrix::SetColumnAlignment(int32_t columnIndex, MathHorizontalAlignment val) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| columnIndex | **int32_t** | Zero-based column index |
| val | [MathHorizontalAlignment](../../mathhorizontalalignment/) | New value of horizontal alignment of specified column |
## Remarks



Example: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->SetColumnAlignment(0, MathHorizontalAlignment::Left);
```

## See Also

* Enum [MathHorizontalAlignment](../../mathhorizontalalignment/)
* Class [MathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)