---
title: set_ExplicitBreak()
second_title: Aspose.Slides för C++ API-referens
description: "Explicit brytning anger om det finns en radbrytning i början av Box-objektet, så att raden bryts i början av box-objektet. Anger antalet operatorer på föregående rad med matematisk text som ska användas som justeringspunkt för den aktuella raden med matematisk text. Möjliga värden: 1..255 Standard: 0 (ingen explicit brytning)"
type: docs
weight: 131
url: /sv/aspose.slides.mathtext/imathbox/set_explicitbreak/
---
## IMathBox::set_ExplicitBreak(uint8_t) metod

Explicit brytning anger om det finns en radbrytning i början av Box-objektet, så att raden bryts vid början av box-objektet. Anger antalet operatorer på föregående rad med matematisk text som ska användas som justeringspunkt för den aktuella raden med matematisk text möjliga värden: 1..255 Standard: 0 (ingen explicit brytning)

```cpp
virtual void Aspose::Slides::MathText::IMathBox::set_ExplicitBreak(uint8_t value)=0
```

## Anmärkningar

Exempel: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_ExplicitBreak(1);
```

## Se också

* Klass [IMathBox](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)