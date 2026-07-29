---
title: Accent()
second_title: Aspose.Slides för C++ API-referens
description: Ställer in ett accenttecken (ett tecken på toppen av detta element)
type: docs
weight: 196
url: /sv/aspose.slides.mathtext/mathelementbase/accent/
---
## MathElementBase::Accent(char16_t) metod


Sätter ett accenttecken (ett tecken på toppen av detta element)

```cpp
System::SharedPtr<IMathAccent> Aspose::Slides::MathText::MathElementBase::Accent(char16_t accentCharacter) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| accentCharacter | char16_t | Accenttecken. Värdet bör ligga inom intervallet (U+0300\\u2013U+036F) eller (U+20D0\\u2013U+20EF) |

### Returvärde

Ny instans av typ [IMathAccent](../../imathaccent/)
## Anmärkningar



Exempel: 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IMathAccent](../../imathaccent/)
* Klass [MathElementBase](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)