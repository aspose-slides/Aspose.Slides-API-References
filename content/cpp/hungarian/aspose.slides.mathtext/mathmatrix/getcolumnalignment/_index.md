---
title: GetColumnAlignment()
second_title: Aspose.Slides C++ API hivatkozás
description: A megadott oszlop vízszintes igazításának lekérdezése
type: docs
weight: 248
url: /hu/aspose.slides.mathtext/mathmatrix/getcolumnalignment/
---
## MathMatrix::GetColumnAlignment(int32_t) metódus


A megadott oszlop vízszintes igazításának lekérdezése

```cpp
MathHorizontalAlignment Aspose::Slides::MathText::MathMatrix::GetColumnAlignment(int32_t columnIndex) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| columnIndex | **int32_t** | Nulla alapú oszlopindex |

### Visszatérési érték

A megadott oszlop vízszintes igazítása
## Megjegyzések



Példa: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
auto alignment = matrix->GetColumnAlignment(0);
```

## Lásd még

* Enum [MathHorizontalAlignment](../../mathhorizontalalignment/)
* Osztály [MathMatrix](../)
* Névtere [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)