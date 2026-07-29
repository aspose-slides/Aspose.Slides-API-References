---
title: get_NoBreak()
second_title: Aspose.Slides för C++ API-referens
description: "Ingen brytning Denna egenskap specificerar den \"obrytbara\" egenskapen på objektboxen. När true, kan inga radbrytningar ske inom boxen. Detta kan vara viktigt för operatoremulatorer som består av mer än en binär operator. När detta element inte specificeras, kan brytningar ske inuti boxen. Standard: true"
type: docs
weight: 40
url: /sv/aspose.slides.mathtext/mathbox/get_nobreak/
---
## MathBox::get_NoBreak() metod

Ingen brytning Denna egenskap specificerar den \"obrytbara\" egenskapen på objektboxen. När true, kan inga radbrytningar ske inom boxen. Detta kan vara viktigt för operatoremulatorer som består av mer än en binär operator. När detta element inte specificeras, kan brytningar ske inuti boxen. Standard: true

```cpp
bool Aspose::Slides::MathText::MathBox::get_NoBreak() override
```

## Anmärkningar

Exempel:
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"*****"));
box->set_NoBreak(false);
```

## Se även

* Klass [MathBox](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)