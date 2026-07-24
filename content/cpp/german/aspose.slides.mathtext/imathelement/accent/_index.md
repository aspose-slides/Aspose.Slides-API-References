---
title: Accent()
second_title: Aspose.Slides für C++ API-Referenz
description: Setzt ein Akzentzeichen (ein Zeichen oben auf diesem Element)
type: docs
weight: 209
url: /de/aspose.slides.mathtext/imathelement/accent/
---
## IMathElement::Accent(char16_t) Methode


Setzt ein Akzentzeichen (ein Zeichen oben auf diesem Element)

```cpp
virtual System::SharedPtr<IMathAccent> Aspose::Slides::MathText::IMathElement::Accent(char16_t accentCharacter)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| accentCharacter | char16_t | Akzentzeichen. Der Wert sollte im Bereich von (U+0300\\u2013U+036F) oder (U+20D0\\u2013U+20EF) liegen. |

### Rückgabewert

Neue Instanz vom Typ [IMathAccent](../../imathaccent/)
## Anmerkungen



Beispiel: 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathAccent](../../imathaccent/)
* Class [IMathElement](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)