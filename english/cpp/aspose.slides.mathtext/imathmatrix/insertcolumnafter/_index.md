---
title: InsertColumnAfter()
second_title: Aspose.Slides for C++ API Reference
description: Insert a new column after the specified one Initially all elements in the new column are null.
type: docs
weight: 326
url: /cpp/aspose.slides.mathtext/imathmatrix/insertcolumnafter/
---
## IMathMatrix::InsertColumnAfter(int32_t) method


Insert a new column after the specified one Initially all elements in the new column are null.

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::InsertColumnAfter(int32_t columnIndex)=0
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

* Class [IMathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)