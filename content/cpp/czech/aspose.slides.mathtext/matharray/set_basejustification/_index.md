---
title: set_BaseJustification()
second_title: Aspose.Slides pro referenci API C++
description: "Určuje zarovnání pole vzhledem k okolnímu textu. Text mimo pole může být zarovnán se spodní, horní nebo střední částí objektu pole. Výchozí hodnota: Center"
type: docs
weight: 27
url: /cs/aspose.slides.mathtext/matharray/set_basejustification/
---
## MathArray::set_BaseJustification(MathVerticalAlignment) metoda


Určuje zarovnání pole vzhledem k okolnímu textu. Text mimo pole může být zarovnán se spodní, horní nebo střední částí objektu pole. Výchozí hodnota: Center

```cpp
void Aspose::Slides::MathText::MathArray::set_BaseJustification(MathVerticalAlignment value) override
```

## Poznámky


Příklad: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_BaseJustification(MathVerticalAlignment::Top);
```

## Viz také

* Enum [MathVerticalAlignment](../../mathverticalalignment/)
* třída [MathArray](../)
* jmenný prostor [Aspose::Slides::MathText](../../)
* knihovna [Aspose.Slides](../../../)