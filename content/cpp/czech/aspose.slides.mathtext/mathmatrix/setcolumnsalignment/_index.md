---
title: SetColumnsAlignment()
second_title: Aspose.Slides pro C++ API Referenci
description: Nastaví vodorovné zarovnání zadaných sloupců
type: docs
weight: 274
url: /cs/aspose.slides.mathtext/mathmatrix/setcolumnsalignment/
---
## MathMatrix::SetColumnsAlignment(int32_t, uint32_t, MathHorizontalAlignment) metoda

Nastaví vodorovné zarovnání zadaných sloupců

```cpp
void Aspose::Slides::MathText::MathMatrix::SetColumnsAlignment(int32_t columnIndex, uint32_t columnsCount, MathHorizontalAlignment val) override
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
* Class [MathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)