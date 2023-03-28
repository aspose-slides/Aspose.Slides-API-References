---
title: SetColumnAlignment()
second_title: Aspose.Slides for C++ API Reference
description: Set the horizontal alignment of the specified column
type: docs
weight: 248
url: /cpp/aspose.slides.mathtext/imathmatrix/setcolumnalignment/
---
## IMathMatrix::SetColumnAlignment(**int32_t**, [MathHorizontalAlignment](../../mathhorizontalalignment/)) method


Set the horizontal alignment of the specified column

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::SetColumnAlignment(int32_t columnIndex, MathHorizontalAlignment val)=0
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
* Class [IMathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
