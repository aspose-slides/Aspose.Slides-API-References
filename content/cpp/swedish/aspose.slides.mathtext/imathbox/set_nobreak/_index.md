---
title: set_NoBreak()
second_title: Aspose.Slides för C++ API-referens
description: "Ingen radbrytning. Denna egenskap specificerar den \"obrytbara\" egenskapen på objektboxen. När true kan inga radbrytningar ske inom boxen. Detta kan vara viktigt för operatoremulatorer som består av mer än en binär operator. När detta element inte anges kan radbrytningar ske inuti boxen. Standard: true"
type: docs
weight: 53
url: /sv/aspose.slides.mathtext/imathbox/set_nobreak/
---
## IMathBox::set_NoBreak(bool) metod

Ingen radbrytning. Denna egenskap anger den "obrytbara" egenskapen på objektboxen. När true kan inga radbrytningar ske inom boxen. Detta kan vara viktigt för operatoremulatorer som består av mer än en binär operator. När detta element inte anges kan radbrytningar ske inuti boxen. Standard: true

```cpp
virtual void Aspose::Slides::MathText::IMathBox::set_NoBreak(bool value)=0
```

## Anmärkningar

Exempel:
```cpp
auto box = System::MakeObject<MathematicalText>(u"**********")->ToBox();
box->set_NoBreak(false);
```

## Se också

* Klass [IMathBox](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)