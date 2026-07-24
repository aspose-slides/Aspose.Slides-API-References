---
title: set_NoBreak()
second_title: Aspose.Slides für C++ API-Referenz
description: "Kein Umbruch Diese Eigenschaft legt die \"unbreakable\"-Eigenschaft für die Objektbox fest. Wenn true, können innerhalb der Box keine Zeilenumbrüche auftreten. Dies kann für Operator-Emulatoren wichtig sein, die aus mehr als einem binären Operator bestehen. Wenn dieses Element nicht angegeben ist, können innerhalb der Box Umbrüche auftreten. Standard: true"
type: docs
weight: 53
url: /de/aspose.slides.mathtext/mathbox/set_nobreak/
---
## MathBox::set_NoBreak(bool) Methode

Kein Umbruch Diese Eigenschaft legt die "unbreakable"-Eigenschaft für die Objektbox fest. Wenn true, können innerhalb der Box keine Zeilenumbrüche auftreten. Dies kann für Operator-Emulatoren wichtig sein, die aus mehr als einem binären Operator bestehen. Wenn dieses Element nicht angegeben ist, können innerhalb der Box Umbrüche auftreten. Standard: true

```cpp
void Aspose::Slides::MathText::MathBox::set_NoBreak(bool value) override
```

## Anmerkungen

Beispiel:
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"*****"));
box->set_NoBreak(false);
```

## Siehe auch

* Klasse [MathBox](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)