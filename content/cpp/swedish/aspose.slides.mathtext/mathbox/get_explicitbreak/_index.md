---
title: get_ExplicitBreak()
second_title: Aspose.Slides för C++ API-referens
description: "Explicit break anger om det finns ett radbrytning i början av Box-objektet, så att raden radbryts i början av Box-objektet. Anger antalet operatorer på den föregående raden med matematisk text som ska användas som justeringspunkt för den aktuella raden med matematisk text möjliga värden: 1..255 Standard: 0 (ingen explicit radbrytning)"
type: docs
weight: 118
url: /sv/aspose.slides.mathtext/mathbox/get_explicitbreak/
---
## MathBox::get_ExplicitBreak() metod

Explicit radbrytning anger om det finns ett radbrytning i början av Box-objektet, så att raden radbryts i början av Box-objektet. Anger antalet operator på den föregående raden av matematisk text som ska användas som justeringspunkt för den aktuella raden av matematisk text möjliga värden: 1..255 Standard: 0 (ingen explicit radbrytning)

```cpp
uint8_t Aspose::Slides::MathText::MathBox::get_ExplicitBreak() override
```

## Anmärkningar


Exempel: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_ExplicitBreak(1);
```

## Se även

* Klass [MathBox](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)