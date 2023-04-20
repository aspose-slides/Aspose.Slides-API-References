---
title: DeleteColumn()
second_title: Aspose.Slides for C++ API Reference
description: Deletes the specified column
type: docs
weight: 352
url: /cpp/aspose.slides.mathtext/mathmatrix/deletecolumn/
---
## MathMatrix::DeleteColumn(int32_t) method


Deletes the specified column

```cpp
void Aspose::Slides::MathText::MathMatrix::DeleteColumn(int32_t columnIndex) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| columnIndex | **int32_t** | The zero-based index of the column to delete. |
## Remarks



Example: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->DeleteColumn(0);
```

## See Also

* Class [MathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)