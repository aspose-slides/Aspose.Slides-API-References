---
title: get_ExplicitBreak()
second_title: Aspose.Slides für C++ API-Referenz
description: "Der explizite Umbruch gibt an, ob am Anfang des Box-Objekts ein Zeilenumbruch vorhanden ist, sodass die Zeile am Anfang des Box-Objekts umbrochen wird. Gibt die Nummer des Operators in der vorherigen Zeile des mathematischen Textes an, die als Ausrichtungspunkt für die aktuelle Zeile des mathematischen Textes verwendet wird. Mögliche Werte: 1..255 Standard: 0 (kein expliziter Umbruch)"
type: docs
weight: 118
url: /de/aspose.slides.mathtext/mathbox/get_explicitbreak/
---
## MathBox::get_ExplicitBreak() Methode

Der explizite Umbruch gibt an, ob am Anfang des Box-Objekts ein Zeilenumbruch vorhanden ist, sodass die Zeile am Anfang des Box-Objekts umbrochen wird. Gibt die Nummer des Operators in der vorherigen Zeile des mathematischen Textes an, die als Ausrichtungspunkt für die aktuelle Zeile des mathematischen Textes verwendet wird. Mögliche Werte: 1..255 Standard: 0 (kein expliziter Umbruch)

```cpp
uint8_t Aspose::Slides::MathText::MathBox::get_ExplicitBreak() override
```

## Anmerkungen

Beispiel: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_ExplicitBreak(1);
```

## Siehe auch

* Klasse [MathBox](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)