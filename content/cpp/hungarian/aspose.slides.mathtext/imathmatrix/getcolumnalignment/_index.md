---
title: GetColumnAlignment()
second_title: Aspose.Slides C++ API referenciája
description: A megadott oszlop vízszintes igazítását adja vissza
type: docs
weight: 235
url: /hu/aspose.slides.mathtext/imathmatrix/getcolumnalignment/
---
## IMathMatrix::GetColumnAlignment(int32_t) metódus


A megadott oszlop vízszintes igazítását adja vissza

```cpp
virtual MathHorizontalAlignment Aspose::Slides::MathText::IMathMatrix::GetColumnAlignment(int32_t columnIndex)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| columnIndex | **int32_t** | Nulla-alapú oszlopindex |

### Visszatérési érték

A megadott oszlop vízszintes igazítása
## Megjegyzések



Példa: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
auto alignment = matrix->GetColumnAlignment(0);
```

## Lásd még

* Enumeráció [MathHorizontalAlignment](../../mathhorizontalalignment/)
* Osztály [IMathMatrix](../)
* Névtere [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)