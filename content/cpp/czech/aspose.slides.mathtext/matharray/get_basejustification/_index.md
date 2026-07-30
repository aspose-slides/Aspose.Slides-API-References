---
title: get_BaseJustification()
second_title: Aspose.Slides pro C++ – reference API
description: "Určuje zarovnání pole vzhledem k okolnímu textu. Text mimo pole může být zarovnán na spodní, horní nebo střed objektu pole. Výchozí hodnota: Center"
type: docs
weight: 14
url: /cs/aspose.slides.mathtext/matharray/get_basejustification/
---
## MathArray::get_BaseJustification() metoda

Určuje zarovnání pole vzhledem k okolnímu textu. Text mimo pole může být zarovnán na spodní, horní nebo střed pole. Výchozí hodnota: Center

```cpp
MathVerticalAlignment Aspose::Slides::MathText::MathArray::get_BaseJustification() override
```

## Poznámky

Příklad:
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_BaseJustification(MathVerticalAlignment::Top);
```

## Viz také

* Výčet [MathVerticalAlignment](../../mathverticalalignment/)
* Třída [MathArray](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)