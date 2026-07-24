---
title: get_ExplicitBreak()
second_title: Aspose.Slides für C++ API Referenz
description: "Expliziter Zeilenumbruch gibt an, ob am Anfang des Box-Objekts ein Zeilenumbruch vorhanden ist, sodass die Zeile am Anfang des Box-Objekts umgebrochen wird. Gibt die Nummer des Operators in der vorherigen Zeile mathematischen Textes an, die als Ausrichtungspunkt für die aktuelle Zeile mathematischen Textes verwendet werden soll. Mögliche Werte: 1..255 Standard: 0 (kein expliziter Zeilenumbruch)"
type: docs
weight: 118
url: /de/aspose.slides.mathtext/imathbox/get_explicitbreak/
---
## IMathBox::get_ExplicitBreak() Methode


Expliziter Zeilenumbruch gibt an, ob am Anfang des Box-Objekts ein Zeilenumbruch vorhanden ist, sodass die Zeile am Anfang des Box-Objekts umbrochen wird. Gibt die Nummer des Operators in der vorherigen Zeile mathematischer Texte an, der als Ausrichtungspunkt für die aktuelle Zeile mathematischer Texte verwendet werden soll. Mögliche Werte: 1..255 Standard: 0 (kein expliziter Zeilenumbruch)

```cpp
virtual uint8_t Aspose::Slides::MathText::IMathBox::get_ExplicitBreak()=0
```

## Hinweise


Beispiel: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_ExplicitBreak(1);
```

## Siehe auch

* Klasse [IMathBox](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)