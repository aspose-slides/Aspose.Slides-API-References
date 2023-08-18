---
title: DeleteRow()
second_title: Aspose.Slides for C++ API Reference
description: Deletes the specified row
type: docs
weight: 300
url: /aspose.slides.mathtext/imathmatrix/deleterow/
---
## IMathMatrix::DeleteRow(int32_t) method


Deletes the specified row

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::DeleteRow(int32_t rowIndex)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| rowIndex | **int32_t** | The zero-based index of the row to delete. |
## Remarks



Example: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->DeleteRow(0);
```

## See Also

* Class [IMathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)