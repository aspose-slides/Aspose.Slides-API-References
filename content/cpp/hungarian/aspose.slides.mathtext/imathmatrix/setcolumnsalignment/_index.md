---
title: SetColumnsAlignment()
second_title: Aspose.Slides C++ API referencia
description: A megadott oszlopok vízszintes igazításának beállítása
type: docs
weight: 261
url: /hu/aspose.slides.mathtext/imathmatrix/setcolumnsalignment/
---
## IMathMatrix::SetColumnsAlignment(int32_t, uint32_t, MathHorizontalAlignment) metódus


A megadott oszlopok vízszintes igazításának beállítása

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::SetColumnsAlignment(int32_t columnIndex, uint32_t columnsCount, MathHorizontalAlignment val)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| columnIndex | **int32_t** | Nulláról induló index az első oszlophoz, amelynek az igazítását be kell állítani |
| columnsCount | **uint32_t** | Az igazítás beállításához szükséges oszlopok száma |
| val | [MathHorizontalAlignment](../../mathhorizontalalignment/) | Az adott oszlop vízszintes igazításának új értéke |
## Megjegyzések



Példa: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->SetColumnsAlignment(0, 3, MathHorizontalAlignment::Left);
```

## Lásd még

* Enumeráció [MathHorizontalAlignment](../../mathhorizontalalignment/)
* Osztály [IMathMatrix](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)