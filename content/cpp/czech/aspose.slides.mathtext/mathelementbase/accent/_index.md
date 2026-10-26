---
title: Accent()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Nastaví diakritický znak (znak na horní části tohoto prvku)
type: docs
weight: 196
url: /cs/aspose.slides.mathtext/mathelementbase/accent/
---
## MathElementBase::Accent(char16_t) metoda

Nastaví diakritický znak (znak na horní části tohoto prvku)

```cpp
System::SharedPtr<IMathAccent> Aspose::Slides::MathText::MathElementBase::Accent(char16_t accentCharacter) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| accentCharacter | char16_t | Znak diakritiky. Hodnota by měla být v rozsahu (U+0300\\u2013U+036F) nebo (U+20D0\\u2013U+20EF) |

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
* Třída [MathElementBase](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)