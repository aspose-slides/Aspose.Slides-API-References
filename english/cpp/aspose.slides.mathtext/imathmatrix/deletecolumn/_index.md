---
title: DeleteColumn()
second_title: Aspose.Slides for C++ API Reference
description: Deletes the specified column
type: docs
weight: 339
url: /cpp/aspose.slides.mathtext/imathmatrix/deletecolumn/
---
## IMathMatrix::DeleteColumn(int32_t) method


Deletes the specified column

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::DeleteColumn(int32_t columnIndex)=0
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

* Class [IMathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)