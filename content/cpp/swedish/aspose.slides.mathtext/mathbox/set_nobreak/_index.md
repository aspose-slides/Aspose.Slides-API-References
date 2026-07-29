---
title: set_NoBreak()
second_title: Aspose.Slides för C++ API-referens
description: "Ingen radbrytning Denna egenskap specificerar den \"ofraktbara\" egenskapen på objektboxen. När sann kan inga radbrytningar inträffa i boxen. Detta kan vara viktigt för operator-emulatorer som består av mer än en binär operator. När detta element inte anges kan radbrytningar inträffa i boxen. Standard: true"
type: docs
weight: 53
url: /sv/aspose.slides.mathtext/mathbox/set_nobreak/
---
## MathBox::set_NoBreak(bool) metod

Ingen radbrytning Den här egenskapen specificerar den \"ofraktbara\" egenskapen på objektboxen. När sann får ingen radbrytning inträffa inom boxen. Detta kan vara viktigt för operator-emulatorer som består av mer än en binär operator. När detta element inte anges kan radbrytningar inträffa inuti boxen. Standard: true

```cpp
void Aspose::Slides::MathText::MathBox::set_NoBreak(bool value) override
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