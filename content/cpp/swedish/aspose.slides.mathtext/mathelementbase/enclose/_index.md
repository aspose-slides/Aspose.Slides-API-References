---
title: Enclose()
second_title: Aspose.Slides för C++ API-referens
description: Innesluter ett matematiskt element i parentes
type: docs
weight: 27
url: /sv/aspose.slides.mathtext/mathelementbase/enclose/
---
## MathElementBase::Enclose() metod


Innesluter ett matematiskt element i parentes

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathElementBase::Enclose() override
```


### Returvärde

Det matematiska elementet av typen [IMathDelimiter](../../imathdelimiter/) som inkluderar parentesen
## Anmärkningar



Exempel: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = element->Enclose();
```

## MathElementBase::Enclose(char16_t, char16_t) metod


Innesluter ett matematiskt element i specificerade tecken, till exempel parentes eller andra tecken som ram

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathElementBase::Enclose(char16_t beginningCharacter, char16_t endingCharacter) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| beginningCharacter | char16_t | Inledande tecken (vanligtvis vänsterklammer) |
| endingCharacter | char16_t | Avslutande tecken (vanligtvis högerklammer) |

### Returvärde

Det matematiska elementet av typen [IMathDelimiter](../../imathdelimiter/) som inkluderar specificerade tecken som ram
## Anmärkningar



Exempel: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = element->Enclose(u'[', u']');
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IMathDelimiter](../../imathdelimiter/)
* Klass [MathElementBase](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)