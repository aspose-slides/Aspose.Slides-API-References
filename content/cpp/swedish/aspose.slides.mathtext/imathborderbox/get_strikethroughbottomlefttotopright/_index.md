---
title: get_StrikethroughBottomLeftToTopRight()
second_title: Aspose.Slides för C++ API-referens
description: Genomstrykning nedre vänstra till övre högra (standard är false). Anger om en genomstrykning diagonal linje från det nedre vänstra hörnet till det övre högra hörnet av ramrutan är dold eller visad.
type: docs
weight: 170
url: /sv/aspose.slides.mathtext/imathborderbox/get_strikethroughbottomlefttotopright/
---
## IMathBorderBox::get_StrikethroughBottomLeftToTopRight() metod

Genomstrykning nedre vänstra till övre högra (standard är false). Anger det dolda eller visade tillståndet för en genomstrykning diagonallinje från det nedre vänstra hörnet till det övre högra hörnet av ramruta.

```cpp
virtual bool Aspose::Slides::MathText::IMathBorderBox::get_StrikethroughBottomLeftToTopRight()=0
```

## Anmärkningar


Exempel: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
borderBox->set_StrikethroughBottomLeftToTopRight(true);
```

## Se även

* Klass [IMathBorderBox](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)