---
title: get_NoBreak()
second_title: Aspose.Slides för C++ API-referens
description: "Ingen brytning. Denna egenskap specificerar egenskapen \"unbreakable\" på objektboxen. När true kan inga radbrytningar förekomma inom boxen. Detta kan vara viktigt för operatoremulatorer som består av mer än en binär operator. När detta element inte är specificerat kan brytningar förekomma i boxen. Standard: true"
type: docs
weight: 40
url: /sv/aspose.slides.mathtext/imathbox/get_nobreak/
---
## IMathBox::get_NoBreak() metod


Ingen brytning. Denna egenskap anger den \"unbreakable\"-egenskapen på objektboxen. När true kan inga radbrytningar förekomma inom boxen. Detta kan vara viktigt för operatoremulatorer som består av mer än en binär operator. När detta element inte är specificerat kan brytningar förekomma inuti boxen. Standard: true

```cpp
virtual bool Aspose::Slides::MathText::IMathBox::get_NoBreak()=0
```

## Anmärkningar


Exempel: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"**********")->ToBox();
box->set_NoBreak(false);
```

## Se även

* Klass [IMathBox](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)