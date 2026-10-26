---
title: Accent()
second_title: Aspose.Slides for C++ API referencia
description: Beállít egy ékezetjelet (az elem tetején lévő karakter)
type: docs
weight: 196
url: /hu/aspose.slides.mathtext/mathelementbase/accent/
---
## MathElementBase::Accent(char16_t) metódus

Beállít egy ékezetjelző jelet (az elem tetején lévő karaktert)

```cpp
System::SharedPtr<IMathAccent> Aspose::Slides::MathText::MathElementBase::Accent(char16_t accentCharacter) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| accentCharacter | char16_t | Ékezet karakter. Az értéknek a (U+0300\u2013U+036F) vagy (U+20D0\u2013U+20EF) tartományon belül kell lennie. |

### Visszatérési érték

Új példány a(z) [IMathAccent](../../imathaccent/) típusból
## Megjegyzések



Példa: 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathAccent](../../imathaccent/)
* Osztály [MathElementBase](../)
* Névterület [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)