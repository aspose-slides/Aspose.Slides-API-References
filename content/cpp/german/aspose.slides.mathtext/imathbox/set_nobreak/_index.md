---
title: set_NoBreak()
second_title: Aspose.Slides für C++ API-Referenz
description: "Kein Umbruch. Diese Eigenschaft legt die \"unbreakable\"-Eigenschaft für die Objektbox fest. Wenn true, können innerhalb der Box keine Zeilenumbrüche auftreten. Dies kann für Operator-Emulatoren wichtig sein, die aus mehr als einem Binäroperator bestehen. Wenn dieses Element nicht angegeben ist, können innerhalb der Box Umbrüche auftreten. Default: true"
type: docs
weight: 53
url: /de/aspose.slides.mathtext/imathbox/set_nobreak/
---
## IMathBox::set_NoBreak(bool) Methode


Kein Umbruch. Diese Eigenschaft legt die \"unbreakable\"-Eigenschaft für die Objektbox fest. Wenn true, können innerhalb der Box keine Zeilenumbrüche auftreten. Dies kann für Operator-Emulatoren wichtig sein, die aus mehr als einem Binäroperator bestehen. Wenn dieses Element nicht angegeben ist, können innerhalb der Box Umbrüche auftreten. Default: true

```cpp
virtual void Aspose::Slides::MathText::IMathBox::set_NoBreak(bool value)=0
```

## Bemerkungen


Beispiel: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"**********")->ToBox();
box->set_NoBreak(false);
```

## Siehe auch

* Klasse [IMathBox](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)