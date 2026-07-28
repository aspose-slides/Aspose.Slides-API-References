---
title: SetColumnAlignment()
second_title: Aspose.Slides C++ API hivatkozás
description: Beállítja a megadott oszlop vízszintes igazítását
type: docs
weight: 261
url: /hu/aspose.slides.mathtext/mathmatrix/setcolumnalignment/
---
## MathMatrix::SetColumnAlignment(int32_t, MathHorizontalAlignment) method

Beállítja a megadott oszlop vízszintes igazítását

```cpp
void Aspose::Slides::MathText::MathMatrix::SetColumnAlignment(int32_t columnIndex, MathHorizontalAlignment val) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| columnIndex | **int32_t** | Nullától kezdődő oszlopindex |
| val | [MathHorizontalAlignment](../../mathhorizontalalignment/) | Az adott oszlop vízszintes igazításának új értéke |
## Megjegyzés



Példa: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->SetColumnAlignment(0, MathHorizontalAlignment::Left);
```

## Lásd még

* Enum [MathHorizontalAlignment](../../mathhorizontalalignment/)
* Osztály [MathMatrix](../)
* Névterület [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)