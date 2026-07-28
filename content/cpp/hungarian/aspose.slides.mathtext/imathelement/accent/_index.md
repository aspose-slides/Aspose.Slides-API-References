---
title: Accent()
second_title: Aspose.Slides C++ API hivatkozás
description: Beállít egy hangsúlyjelet (egy karakter az elem tetején)
type: docs
weight: 209
url: /hu/aspose.slides.mathtext/imathelement/accent/
---
## IMathElement::Accent(char16_t) metódus

Beállít egy hangsúlyjelet (a karaktert ennek az elemnek a tetején)

```cpp
virtual System::SharedPtr<IMathAccent> Aspose::Slides::MathText::IMathElement::Accent(char16_t accentCharacter)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| accentCharacter | char16_t | Hangsúly karakter. Az értéknek a (U+0300\\u2013U+036F) vagy (U+20D0\\u2013U+20EF) tartományon belül kell lennie. |

### Visszatérési érték

Új példány a(z) [IMathAccent](../../imathaccent/) típusból

## Megjegyzés

Példa: 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathAccent](../../imathaccent/)
* Osztály [IMathElement](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)