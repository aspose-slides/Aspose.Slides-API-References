---
title: get_BaseJustification()
second_title: Aspose.Slides för C++ API-referens
description: "Specificerar justeringen av matrisen i förhållande till omgivande text. Text utanför matrisen kan justeras med bottom, top, eller center av ett matrisobjekt. Standardvärde: Center"
type: docs
weight: 14
url: /sv/aspose.slides.mathtext/imatharray/get_basejustification/
---
## IMathArray::get_BaseJustification() metod

Specificerar justeringen av matrisen i förhållande till omgivande text. Text utanför matrisen kan justeras med botten, toppen eller mitten av ett matrisobjekt. Standardvärde: Center

```cpp
virtual MathVerticalAlignment Aspose::Slides::MathText::IMathArray::get_BaseJustification()=0
```

## Anmärkningar

Exempel: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_BaseJustification(MathVerticalAlignment::Top);
```

## Se också

* Enum [MathVerticalAlignment](../../mathverticalalignment/)
* Klass [IMathArray](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)