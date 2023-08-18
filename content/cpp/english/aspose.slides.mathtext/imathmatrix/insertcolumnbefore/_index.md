---
title: InsertColumnBefore()
second_title: Aspose.Slides for C++ API Reference
description: Insert a new column before the specified one Initially all elements in the new column are null.
type: docs
weight: 313
url: /aspose.slides.mathtext/imathmatrix/insertcolumnbefore/
---
## IMathMatrix::InsertColumnBefore(int32_t) method


Insert a new column before the specified one Initially all elements in the new column are null.

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::InsertColumnBefore(int32_t columnIndex)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| columnIndex | **int32_t** | Index of the column before which to insert a new one |
## Remarks



Example: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertColumnBefore(0);
```

## See Also

* Class [IMathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)