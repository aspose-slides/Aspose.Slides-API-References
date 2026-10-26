---
title: SetSubSuperscriptOnTheLeft()
second_title: Aspose.Slides voor C++ API-referentie
description: Creëert subscript en superscript aan de linkerkant
type: docs
weight: 118
url: /nl/aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft/
---
## IMathElement::SetSubSuperscriptOnTheLeft(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) methode


Creëert subscript en superscript aan de linkerkant

```cpp
virtual System::SharedPtr<IMathLeftSubSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSubSuperscriptOnTheLeft(System::SharedPtr<IMathElement> subscript, System::SharedPtr<IMathElement> superscript)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Subscript (lagere index aan de linkerkant) |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Superscript (hogere index aan de linkerkant) |

### Retourwaarde

Nieuw wiskundig element van type [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)
## Opmerkingen



Voorbeeld: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto leftSubsuperscript = baseElement->SetSubSuperscriptOnTheLeft(subscript, superscript);
```

## IMathElement::SetSubSuperscriptOnTheLeft(System::String, System::String) methode


Creëert subscript en superscript aan de linkerkant

```cpp
virtual System::SharedPtr<IMathLeftSubSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSubSuperscriptOnTheLeft(System::String subscript, System::String superscript)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | Subscript (lagere index aan de linkerkant) |
| superscript | [System::String](../../../system/string/) | Superscript (hogere index aan de linkerkant) |

### Retourwaarde

Nieuw wiskundig element van type [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)
## Opmerkingen



Voorbeeld: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto leftSubsuperscript = baseElement->SetSubSuperscriptOnTheLeft(u"i", u"j");
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)
* Klasse [IMathElement](../)
* Klasse [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)