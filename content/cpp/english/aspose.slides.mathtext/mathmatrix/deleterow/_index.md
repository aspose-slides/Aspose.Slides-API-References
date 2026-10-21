---
title: DeleteRow()
second_title: Aspose.Slides for C++ API Reference
description: Deletes the specified row
type: docs
weight: 313
url: /aspose.slides.mathtext/mathmatrix/deleterow/
---
## MathMatrix::DeleteRow(int32_t) method


Deletes the specified row

```cpp
void Aspose::Slides::MathText::MathMatrix::DeleteRow(int32_t rowIndex) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| rowIndex | **int32_t** | The zero-based index of the row to delete. |

### Exceptions

| Exception | Description |
| --- | --- |
| [System::InvalidOperationException](../../../system/invalidoperationexception/) | When you try to delete the last single row in the matrix |
| [System::ArgumentOutOfRangeException](../../../system/argumentoutofrangeexception/) | If rowIndex less than zero or greater or equal to the RowCount |

## Remarks



Example: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->DeleteRow(0);
```

## See Also

* Class [MathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)