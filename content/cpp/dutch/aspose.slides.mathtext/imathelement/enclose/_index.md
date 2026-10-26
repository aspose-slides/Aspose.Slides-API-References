---
title: Enclose()
second_title: Aspose.Slides voor C++ API Referentie
description: Omvat een wiskundig element tussen haakjes
type: docs
weight: 40
url: /nl/aspose.slides.mathtext/imathelement/enclose/
---
## IMathElement::Enclose() methode


Omvat een wiskundig element tussen haakjes

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathElement::Enclose()=0
```


### Retourwaarde

Het wiskundige element van type [IMathDelimiter](../../imathdelimiter/) dat de haakjes bevat
## Opmerkingen



Voorbeeld: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = element->Enclose();
```

## IMathElement::Enclose(char16_t, char16_t) methode


Omvat dit element in opgegeven tekens, zoals haakjes of andere tekens als omkadering

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathElement::Enclose(char16_t beginningCharacter, char16_t endingCharacter)=0
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| beginningCharacter | char16_t | Beginteken (meestal linker haakje) |
| endingCharacter | char16_t | Eindteken (meestal rechter haakje) |

### Retourwaarde

Het wiskundige element van type [IMathDelimiter](../../imathdelimiter/) dat de opgegeven tekens als kader bevat
## Opmerkingen



Voorbeeld: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = element->Enclose(u'[', u']');
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathDelimiter](../../imathdelimiter/)
* Class [IMathElement](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)