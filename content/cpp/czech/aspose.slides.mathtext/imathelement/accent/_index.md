---
title: Accent()
second_title: Aspose.Slides pro C++ reference API
description: Nastaví akcentový znak (znak umístěný nad tímto prvkem)
type: docs
weight: 209
url: /cs/aspose.slides.mathtext/imathelement/accent/
---
## IMathElement::Accent(char16_t) metoda


Nastaví akcentový znak (znak umístěný nad tímto prvkem)

```cpp
virtual System::SharedPtr<IMathAccent> Aspose::Slides::MathText::IMathElement::Accent(char16_t accentCharacter)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| accentCharacter | char16_t | Akcentový znak. Hodnota by měla být v rozsahu (U+0300\u2013U+036F) nebo (U+20D0\u2013U+20EF) |

### Návratová hodnota

Nová instance typu [IMathAccent](../../imathaccent/)
## Poznámky



Příklad: 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IMathAccent](../../imathaccent/)
* Třída [IMathElement](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)