---
title: set_Character()
second_title: Aspose.Slides für C++ API-Referenz
description: "Akzentzeichen Der Wert sollte im Bereich von (U+0300\\u2013U+036F) oder(U+20D0\\u2013U+20EF) liegen. Standardwert: Kombinierender Zirkumflexakzent (U+0302)"
type: docs
weight: 27
url: /de/aspose.slides.mathtext/imathaccent/set_character/
---
## IMathAccent::set_Character(char16_t) Methode

Akzentzeichen Der Wert sollte im Bereich von (U+0300\\u2013U+036F) oder(U+20D0\\u2013U+20EF) liegen. Standardwert: Kombinierender Zirkumflexakzent (U+0302)

```cpp
virtual void Aspose::Slides::MathText::IMathAccent::set_Character(char16_t value)=0
```

## Anmerkungen


Beispiel: 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
char16_t ch = accent->get_Character();
```

## Siehe auch

* Klasse [IMathAccent](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)