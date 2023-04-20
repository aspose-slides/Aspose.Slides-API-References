---
title: InsertColumnAfter()
second_title: Aspose.Slides for C++ API Reference
description: Insert a new column after the specified one Initially all elements in the new column are null.
type: docs
weight: 339
url: /cpp/aspose.slides.mathtext/mathmatrix/insertcolumnafter/
---
## MathMatrix::InsertColumnAfter(int32_t) method


Insert a new column after the specified one Initially all elements in the new column are null.

```cpp
void Aspose::Slides::MathText::MathMatrix::InsertColumnAfter(int32_t columnIndex) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| columnIndex | **int32_t** | Index of the column after which to insert a new one |
## Remarks



Example: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertColumnAfter(0);
```

## See Also

* Class [MathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)