---
title: get_BaseJustification()
second_title: Aspose.Slides för C++ API-referens
description: "Specificerar justeringen av matrisen i förhållande till omgivande text. Text utanför matrisen kan justeras med botten, toppen eller mitten av ett matrisobjekt. Standardvärde: Center"
type: docs
weight: 14
url: /sv/aspose.slides.mathtext/matharray/get_basejustification/
---
## MathArray::get_BaseJustification() metod

Specificerar justeringen av matrisen i förhållande till omgivande text. Text utanför matrisen kan justeras med botten, toppen eller mitten av ett matrisobjekt. Standardvärde: Center

```cpp
MathVerticalAlignment Aspose::Slides::MathText::MathArray::get_BaseJustification() override
```

## Anmärkningar

Exempel: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_BaseJustification(MathVerticalAlignment::Top);
```

## Se även

* Enum [MathVerticalAlignment](../../mathverticalalignment/)
* Klass [MathArray](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)