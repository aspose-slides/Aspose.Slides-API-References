---
title: SetColumnsAlignment()
second_title: Aspose.Slides for C++ API-referencia
description: Beállítja a megadott oszlopok vízszintes igazítását
type: docs
weight: 274
url: /hu/aspose.slides.mathtext/mathmatrix/setcolumnsalignment/
---
## MathMatrix::SetColumnsAlignment(int32_t, uint32_t, MathHorizontalAlignment) metódus

Beállítja a megadott oszlopok vízszintes igazítását

```cpp
void Aspose::Slides::MathText::MathMatrix::SetColumnsAlignment(int32_t columnIndex, uint32_t columnsCount, MathHorizontalAlignment val) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| columnIndex | **int32_t** | Nullától kezdődő index az első oszlophoz, amelynek az igazítását be kell állítani |
| columnsCount | **uint32_t** | Az igazítás megadásához szükséges oszlopok száma |
| val | [MathHorizontalAlignment](../../mathhorizontalalignment/) | Az adott oszlop vízszintes igazításának új értéke |
## Megjegyzések

Példa: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->SetColumnsAlignment(0, 3, MathHorizontalAlignment::Left);
```

## Lásd még

* Enum [MathHorizontalAlignment](../../mathhorizontalalignment/)
* Osztály [MathMatrix](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)