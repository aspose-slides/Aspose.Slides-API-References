---
title: DeleteRow()
second_title: Aspose.Slides C++ API referenciája
description: Törli a megadott sort
type: docs
weight: 313
url: /hu/aspose.slides.mathtext/mathmatrix/deleterow/
---
## MathMatrix::DeleteRow(int32_t) method

Törli a megadott sort

```cpp
void Aspose::Slides::MathText::MathMatrix::DeleteRow(int32_t rowIndex) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| rowIndex | **int32_t** | A sor nulla alapú indexe, amelyet törölni kell. |
## Megjegyzések



Példa: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->DeleteRow(0);
```

## Lásd még

* Osztály [MathMatrix](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)