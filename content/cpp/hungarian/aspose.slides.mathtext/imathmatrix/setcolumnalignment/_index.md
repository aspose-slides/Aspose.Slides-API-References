---
title: SetColumnAlignment()
second_title: Aspose.Slides C++ API Referencia
description: Állítsa be a megadott oszlop vízszintes igazítását
type: docs
weight: 248
url: /hu/aspose.slides.mathtext/imathmatrix/setcolumnalignment/
---
## IMathMatrix::SetColumnAlignment(int32_t, MathHorizontalAlignment) metódus

Állítsa be a megadott oszlop vízszintes igazítását

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::SetColumnAlignment(int32_t columnIndex, MathHorizontalAlignment val)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| columnIndex | **int32_t** | Nulla alapú oszlop index |
| val | [MathHorizontalAlignment](../../mathhorizontalalignment/) | Az adott oszlop vízszintes igazításának új értéke |

## Megjegyzések



Példa: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->SetColumnAlignment(0, MathHorizontalAlignment::Left);
```

## Lásd még

* Enum [MathHorizontalAlignment](../../mathhorizontalalignment/)
* Osztály [IMathMatrix](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)