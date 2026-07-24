---
title: get_Character()
second_title: Aspose.Slides für C++ API-Referenz
description: "Akzentzeichen Der Wert sollte im Bereich von (U+0300\\u2013U+036F) oder(U+20D0\\u2013U+20EF) Standardwert: Combining Circumflex Accent (U+0302)"
type: docs
weight: 14
url: /de/aspose.slides.mathtext/imathaccent/get_character/
---
## IMathAccent::get_Character() Methode

Akzentzeichen Der Wert sollte im Bereich von (U+0300\\u2013U+036F) oder (U+20D0\\u2013U+20EF) Standardwert: Combining Circumflex Accent (U+0302)

```cpp
virtual char16_t Aspose::Slides::MathText::IMathAccent::get_Character()=0
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