---
title: Accent()
second_title: Aspose.Slides für C++ API-Referenz
description: Setzt ein Akzentzeichen (ein Zeichen oben auf diesem Element)
type: docs
weight: 196
url: /de/aspose.slides.mathtext/mathelementbase/accent/
---
## MathElementBase::Accent(char16_t) Methode

Setzt ein Akzentzeichen (ein Zeichen oben auf diesem Element)

```cpp
System::SharedPtr<IMathAccent> Aspose::Slides::MathText::MathElementBase::Accent(char16_t accentCharacter) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| accentCharacter | char16_t | Akzentzeichen. Der Wert sollte im Bereich von (U+0300\\u2013U+036F) oder (U+20D0\\u2013U+20EF) liegen. |

### Rückgabewert

Neue Instanz des Typs [IMathAccent](../../imathaccent/)

## Anmerkungen

Beispiel: 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathAccent](../../imathaccent/)
* Klasse [MathElementBase](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)