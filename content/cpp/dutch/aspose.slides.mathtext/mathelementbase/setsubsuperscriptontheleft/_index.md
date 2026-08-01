---
title: SetSubSuperscriptOnTheLeft()
second_title: Aspose.Slides for C++ API-referentie
description: Creëert subscript en superscript aan de linkerkant
type: docs
weight: 105
url: /nl/aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft/
---
## MathElementBase::SetSubSuperscriptOnTheLeft(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) method


Creëert subscript en superscript aan de linkerkant

```cpp
System::SharedPtr<IMathLeftSubSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubSuperscriptOnTheLeft(System::SharedPtr<IMathElement> subscript, System::SharedPtr<IMathElement> superscript) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Subscript (lager index aan de linkerkant) |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Superscript (hoger index aan de linkerkant) |

### Retourwaarde

Nieuw wiskundig element van het type [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)
## Opmerkingen



Voorbeeld: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto leftSubsuperscript = baseElement->SetSubSuperscriptOnTheLeft(subscript, superscript);
```

## MathElementBase::SetSubSuperscriptOnTheLeft(System::String, System::String) method


Creëert subscript en superscript aan de linkerkant

```cpp
System::SharedPtr<IMathLeftSubSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubSuperscriptOnTheLeft(System::String subscript, System::String superscript) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | Subscript (lager index aan de linkerkant) |
| superscript | [System::String](../../../system/string/) | Superscript (hoger index aan de linkerkant) |

### Retourwaarde

Nieuw wiskundig element van het type [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)
## Opmerkingen



Voorbeeld: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto leftSubsuperscript = baseElement->SetSubSuperscriptOnTheLeft(u"i", u"j");
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)
* Class [IMathElement](../../imathelement/)
* Class [MathElementBase](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)