---
title: get_Character()
second_title: Aspose.Slides für C++ API-Referenz
description: "Akzentzeichen Der Wert sollte innerhalb des Bereichs (U+0300\\u2013U+036F) oder(U+20D0\\u2013U+20EF) liegen. Standardwert: Kombinierender Zirkumflex-Akzent (U+0302)"
type: docs
weight: 14
url: /de/aspose.slides.mathtext/mathaccent/get_character/
---
## MathAccent::get_Character() Methode

Akzentzeichen Der Wert sollte innerhalb des Bereichs (U+0300\\u2013U+036F) oder (U+20D0\\u2013U+20EF) liegen. Standardwert: Kombinierender Zirkumflex-Akzent (U+0302)

```cpp
char16_t Aspose::Slides::MathText::MathAccent::get_Character() override
```

## Bemerkungen

Beispiel: 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
char16_t ch = accent->get_Character();
```

## Siehe auch

* Klasse [MathAccent](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)