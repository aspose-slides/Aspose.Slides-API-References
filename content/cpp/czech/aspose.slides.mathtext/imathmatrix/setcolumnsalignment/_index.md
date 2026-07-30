---
title: SetColumnsAlignment()
second_title: Aspose.Slides pro C++ API Reference
description: Nastaví vodorovné zarovnání určených sloupců
type: docs
weight: 261
url: /cs/aspose.slides.mathtext/imathmatrix/setcolumnsalignment/
---
## IMathMatrix::SetColumnsAlignment(int32_t, uint32_t, MathHorizontalAlignment) metoda

Nastaví vodorovné zarovnání zadaných sloupců

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::SetColumnsAlignment(int32_t columnIndex, uint32_t columnsCount, MathHorizontalAlignment val)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| columnIndex | **int32_t** | Nulový index prvního sloupce, pro který se nastavuje zarovnání |
| columnsCount | **uint32_t** | Počet sloupců, pro které se určuje zarovnání |
| val | [MathHorizontalAlignment](../../mathhorizontalalignment/) | Nová hodnota vodorovného zarovnání zadaného sloupce |
## Poznámky

Příklad:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->SetColumnsAlignment(0, 3, MathHorizontalAlignment::Left);
```

## Viz také

* Enum [MathHorizontalAlignment](../../mathhorizontalalignment/)
* Třída [IMathMatrix](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)