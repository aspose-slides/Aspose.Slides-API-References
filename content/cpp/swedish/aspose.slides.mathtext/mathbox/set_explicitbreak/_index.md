---
title: set_ExplicitBreak()
second_title: Aspose.Slides för C++ API-referens
description: "Explicit radbrytning anger om det finns en radbrytning i början av Box-objektet, så att raden bryts i början av Box-objektet. Anger antalet operator på föregående rad med matematisk text som ska användas som justeringspunkt för den aktuella raden med matematisk text. Möjliga värden: 1..255. Standard: 0 (ingen explicit radbrytning)"
type: docs
weight: 131
url: /sv/aspose.slides.mathtext/mathbox/set_explicitbreak/
---
## MathBox::set_ExplicitBreak(uint8_t) metod

Explicit radbrytning anger om det finns en radbrytning i början av Box-objektet, så att raden bryts i början av box-objektet. Anger antalet operatorer på föregående rad med matematisk text som ska användas som justeringspunkt för den aktuella raden med matematisk text. Möjliga värden: 1..255. Standardvärde: 0 (ingen explicit radbrytning)

```cpp
void Aspose::Slides::MathText::MathBox::set_ExplicitBreak(uint8_t value) override
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