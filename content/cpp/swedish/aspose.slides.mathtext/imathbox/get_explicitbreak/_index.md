---
title: get_ExplicitBreak()
second_title: Aspose.Slides för C++ API-referens
description: "Explicit brytning anger om det finns en radbrytning i början av Box-objektet, så att raden bryts i början av box-objektet. Anger numret på operatorn på föregående rad med matematisk text som ska användas som justeringspunkt för den aktuella raden med matematisk text. Möjliga värden: 1..255 Standard: 0 (ingen explicit brytning)"
type: docs
weight: 118
url: /sv/aspose.slides.mathtext/imathbox/get_explicitbreak/
---
## IMathBox::get_ExplicitBreak() metod


Explicit brytning anger om det finns en radbrytning i början av Box-objektet, så att raden viker sig i början av box-objektet. Anger numret på operatorn på föregående rad av matematisk text som ska användas som justeringspunkt för den aktuella raden av matematisk text. Möjliga värden: 1..255 Standard: 0 (ingen explicit brytning)

```cpp
virtual uint8_t Aspose::Slides::MathText::IMathBox::get_ExplicitBreak()=0
```

## Anmärkningar


Exempel: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_ExplicitBreak(1);
```

## Se även

* Klass [IMathBox](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)