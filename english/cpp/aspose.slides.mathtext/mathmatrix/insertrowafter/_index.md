---
title: InsertRowAfter()
second_title: Aspose.Slides for C++ API Reference
description: Insert a new row after the specified one Initially all elements in the new row are null.
type: docs
weight: 300
url: /cpp/aspose.slides.mathtext/mathmatrix/insertrowafter/
---
## MathMatrix::InsertRowAfter(int32_t) method


Insert a new row after the specified one Initially all elements in the new row are null.

```cpp
void Aspose::Slides::MathText::MathMatrix::InsertRowAfter(int32_t rowIndex) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| rowIndex | **int32_t** | Index of the row after which to insert a new one |
## Remarks



Example: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertRowAfter(1);
```

## See Also

* Class [MathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)