---
title: get_NoBreak()
second_title: Aspose.Slides für C++ API-Referenz
description: "Kein Umbruch. Diese Eigenschaft legt die \"unbreakable\"-Eigenschaft der Objektbox fest. Wenn true, können innerhalb der Box keine Zeilenumbrüche auftreten. Dies kann für Operator-Emulatoren wichtig sein, die aus mehr als einem binären Operator bestehen. Wenn dieses Element nicht angegeben ist, können innerhalb der Box Umbrüche auftreten. Standard: true"
type: docs
weight: 40
url: /de/aspose.slides.mathtext/imathbox/get_nobreak/
---
## IMathBox::get_NoBreak() Methode


Kein Umbruch. Diese Eigenschaft legt die \"unbreakable\"-Eigenschaft der Objektbox fest. Wenn true, können innerhalb der Box keine Zeilenumbrüche auftreten. Dies kann für Operator-Emulatoren wichtig sein, die aus mehr als einem binären Operator bestehen. Wenn dieses Element nicht angegeben ist, können innerhalb der Box Umbrüche auftreten. Standard: true

```cpp
virtual bool Aspose::Slides::MathText::IMathBox::get_NoBreak()=0
```

## Anmerkungen


Beispiel: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"**********")->ToBox();
box->set_NoBreak(false);
```

## Siehe auch

* Klasse [IMathBox](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)