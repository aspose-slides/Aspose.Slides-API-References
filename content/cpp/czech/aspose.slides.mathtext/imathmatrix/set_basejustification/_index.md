---
title: set_BaseJustification()
second_title: Aspose.Slides pro C++ API Reference
description: "Určuje svislé zarovnání vzhledem k okolnímu textu. Možné hodnoty jsou top, bottom a center. Výchozí: Center"
type: docs
weight: 66
url: /cs/aspose.slides.mathtext/imathmatrix/set_basejustification/
---
## IMathMatrix::set_BaseJustification(MathVerticalAlignment) metoda

Určuje svislé zarovnání vzhledem k okolnímu textu. Možné hodnoty jsou top, bottom a center. Výchozí: Center

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::set_BaseJustification(MathVerticalAlignment value)=0
```

## Poznámky

Příklad:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_BaseJustification(MathVerticalAlignment::Center);
```

## Viz také

* Výčtový typ [MathVerticalAlignment](../../mathverticalalignment/)
* Třída [IMathMatrix](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)