---
title: InsertRowBefore()
second_title: Aspose.Slides for C++ API Reference
description: Insert a new row before the specified one Initially all elements in the new row are null.
type: docs
weight: 274
url: /aspose.slides.mathtext/imathmatrix/insertrowbefore/
---
## IMathMatrix::InsertRowBefore(int32_t) method


Insert a new row before the specified one Initially all elements in the new row are null.

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::InsertRowBefore(int32_t rowIndex)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| rowIndex | **int32_t** | Index of the row before which to insert a new one |
## Remarks



Example: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertRowBefore(1);
```

## See Also

* Class [IMathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)