---
title: set_BaseJustification()
second_title: Aspose.Slides pro C++ API Referenční příručka
description: "Určuje svislé zarovnání vzhledem k okolnímu textu. Možné hodnoty jsou top, bottom a center. Výchozí: Center"
type: docs
weight: 66
url: /cs/aspose.slides.mathtext/mathmatrix/set_basejustification/
---
## MathMatrix::set_BaseJustification(MathVerticalAlignment) metoda


Určuje svislé zarovnání vzhledem k okolnímu textu. Možné hodnoty jsou top, bottom a center. Výchozí: Center

```cpp
void Aspose::Slides::MathText::MathMatrix::set_BaseJustification(MathVerticalAlignment value) override
```

## Poznámky


Příklad: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_BaseJustification(MathVerticalAlignment::Center);
```

## Viz také

* Výčet [MathVerticalAlignment](../../mathverticalalignment/)
* Třída [MathMatrix](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)