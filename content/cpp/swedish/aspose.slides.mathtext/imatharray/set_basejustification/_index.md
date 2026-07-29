---
title: set_BaseJustification()
second_title: Aspose.Slides för C++ API-referens
description: "Anger justering av matrisen i förhållande till omgivande text. Text utanför matrisen kan justeras med botten, toppen eller mitten av ett matrisobjekt. Standardvärde: Center"
type: docs
weight: 27
url: /sv/aspose.slides.mathtext/imatharray/set_basejustification/
---
## IMathArray::set_BaseJustification(MathVerticalAlignment) metod

Anger justering av matrisen i förhållande till omgivande text. Text utanför matrisen kan justeras med botten, toppen eller mitten av ett matrisobjekt. Standardvärde: Center

```cpp
virtual void Aspose::Slides::MathText::IMathArray::set_BaseJustification(MathVerticalAlignment value)=0
```

## Anmärkningar

Exempel:
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_BaseJustification(MathVerticalAlignment::Top);
```

## Se även

* Enum [MathVerticalAlignment](../../mathverticalalignment/)
* Klass [IMathArray](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)