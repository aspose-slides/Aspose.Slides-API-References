---
title: get_NoBreak()
second_title: Aspose.Slides für C++ API-Referenz
description: "Kein Umbruch Diese Eigenschaft legt die \"unbreakable\"-Eigenschaft des Objektfelds fest. Wenn true, können innerhalb des Feldes keine Zeilenumbrüche auftreten. Dies kann für Operator-Emulatoren wichtig sein, die aus mehr als einem binären Operator bestehen. Wenn dieses Element nicht angegeben ist, können innerhalb des Feldes Umbrüche auftreten. Standard: true"
type: docs
weight: 40
url: /de/aspose.slides.mathtext/mathbox/get_nobreak/
---
## MathBox::get_NoBreak() Methode


Kein Umbruch Diese Eigenschaft gibt an, dass die \"unbreakable\"-Eigenschaft für das Objektfeld festgelegt ist. Wenn true, können innerhalb des Feldes keine Zeilenumbrüche auftreten. Dies kann für Operator-Emulatoren wichtig sein, die aus mehr als einem binären Operator bestehen. Wenn dieses Element nicht angegeben ist, können innerhalb des Feldes Umbrüche auftreten. Standard: true

```cpp
bool Aspose::Slides::MathText::MathBox::get_NoBreak() override
```

## Hinweise


Beispiel: 
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"*****"));
box->set_NoBreak(false);
```

## Siehe auch

* Klasse [MathBox](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)