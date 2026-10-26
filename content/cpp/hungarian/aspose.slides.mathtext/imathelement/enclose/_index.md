---
title: Enclose()
second_title: Aspose.Slides C++ API referencia
description: Lezár egy matematikai elemet zárójelek közé
type: docs
weight: 40
url: /hu/aspose.slides.mathtext/imathelement/enclose/
---
## IMathElement::Enclose() metódus


Lezár egy matematikai elemet zárójelek közé

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathElement::Enclose()=0
```


### Visszatérési érték

A [IMathDelimiter](../../imathdelimiter/) típusú matematikai elem, amely tartalmazza a zárójeleket
## Megjegyzések



Példa: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = element->Enclose();
```

## IMathElement::Enclose(char16_t, char16_t) metódus


Lezárja ezt az elemet a megadott karakterek közé, például zárójelek vagy egyéb karakterek keretezésként

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathElement::Enclose(char16_t beginningCharacter, char16_t endingCharacter)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| beginningCharacter | char16_t | Kezdő karakter (általában bal zárójel) |
| endingCharacter | char16_t | Záró karakter (általában jobb zárójel) |

### Visszatérési érték

A [IMathDelimiter](../../imathdelimiter/) típusú matematikai elem, amely tartalmazza a megadott karaktereket keretezésként
## Megjegyzések



Példa: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = element->Enclose(u'[', u']');
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathDelimiter](../../imathdelimiter/)
* Class [IMathElement](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)