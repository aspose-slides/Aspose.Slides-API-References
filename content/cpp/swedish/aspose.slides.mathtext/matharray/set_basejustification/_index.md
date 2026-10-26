---
title: set_BaseJustification()
second_title: Aspose.Slides för C++ API-referens
description: "Specificerar justeringen av arrayen relativt till omgivande text. Text utanför arrayen kan justeras med botten, toppen eller mitten av ett array-objekt. Standardvärde: Center"
type: docs
weight: 27
url: /sv/aspose.slides.mathtext/matharray/set_basejustification/
---
## MathArray::set_BaseJustification(MathVerticalAlignment) method

Specificerar justeringen av arrayen i förhållande till omgivande text. Text utanför arrayen kan justeras med botten, toppen eller mitten av ett array-objekt. Standardvärde: Center

```cpp
void Aspose::Slides::MathText::MathArray::set_BaseJustification(MathVerticalAlignment value) override
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