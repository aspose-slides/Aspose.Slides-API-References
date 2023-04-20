---
title: SetColumnsAlignment()
second_title: Aspose.Slides for C++ API Reference
description: Set the horizontal alignment of the specified columns
type: docs
weight: 274
url: /cpp/aspose.slides.mathtext/mathmatrix/setcolumnsalignment/
---
## MathMatrix::SetColumnsAlignment(int32_t, uint32_t, MathHorizontalAlignment) method


Set the horizontal alignment of the specified columns

```cpp
void Aspose::Slides::MathText::MathMatrix::SetColumnsAlignment(int32_t columnIndex, uint32_t columnsCount, MathHorizontalAlignment val) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| columnIndex | **int32_t** | Zero-based index of the first column to set alignment |
| columnsCount | **uint32_t** | The number of columns to specify the alignment |
| val | [MathHorizontalAlignment](../../mathhorizontalalignment/) | New value of horizontal alignment of specified column |
## Remarks



Example: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->SetColumnsAlignment(0, 3, MathHorizontalAlignment::Left);
```

## See Also

* Enum [MathHorizontalAlignment](../../mathhorizontalalignment/)
* Class [MathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)