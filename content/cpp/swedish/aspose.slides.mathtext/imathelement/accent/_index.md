---
title: Accent()
second_title: Aspose.Slides för C++ API-referens
description: Ställer in ett accenttecken (ett tecken ovanför detta element)
type: docs
weight: 209
url: /sv/aspose.slides.mathtext/imathelement/accent/
---
## IMathElement::Accent(char16_t) metod

Ställer in ett accenttecken (ett tecken ovanför detta element)

```cpp
virtual System::SharedPtr<IMathAccent> Aspose::Slides::MathText::IMathElement::Accent(char16_t accentCharacter)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| accentCharacter | char16_t | Accenttecken. Värdet bör ligga inom intervallet (U+0300\\u2013U+036F) eller (U+20D0\\u2013U+20EF) |

### Returvärde

Ny instans av typen [IMathAccent](../../imathaccent/)
## Anmärkningar



Exempel: 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
```

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IMathAccent](../../imathaccent/)
* Klass [IMathElement](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)