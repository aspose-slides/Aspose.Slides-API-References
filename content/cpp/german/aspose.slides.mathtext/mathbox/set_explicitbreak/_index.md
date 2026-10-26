---
title: set_ExplicitBreak()
second_title: Aspose.Slides für C++ API-Referenz
description: "Ein expliziter Umbruch gibt an, ob am Anfang des Box-Objekts ein Zeilenumbruch vorhanden ist, sodass die Zeile am Anfang des Box-Objekts umbrochen wird. Gibt die Nummer des Operators in der vorherigen Zeile des mathematischen Textes an, die als Ausrichtungspunkt für die aktuelle Zeile des mathematischen Textes verwendet werden soll. Mögliche Werte: 1..255 Standard: 0 (kein expliziter Umbruch)"
type: docs
weight: 131
url: /de/aspose.slides.mathtext/mathbox/set_explicitbreak/
---
## MathBox::set_ExplicitBreak(uint8_t) Methode

Ein expliziter Umbruch gibt an, ob am Anfang des Box-Objekts ein Zeilenumbruch erfolgt, sodass die Zeile am Anfang des Box-Objekts umbrochen wird. Gibt die Nummer des Operators in der vorherigen Zeile des mathematischen Textes an, die als Ausrichtungspunkt für die aktuelle Zeile des mathematischen Textes verwendet werden soll. Mögliche Werte: 1..255 Standard: 0 (kein expliziter Umbruch)

```cpp
void Aspose::Slides::MathText::MathBox::set_ExplicitBreak(uint8_t value) override
```

## Hinweise

Beispiel:
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_ExplicitBreak(1);
```

## Siehe auch

* Klasse [MathBox](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)