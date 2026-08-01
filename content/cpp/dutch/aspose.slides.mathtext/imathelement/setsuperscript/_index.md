---
title: SetSuperscript()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt superscript
type: docs
weight: 92
url: /nl/aspose.slides.mathtext/imathelement/setsuperscript/
---
## IMathElement::SetSuperscript(System::SharedPtr\<IMathElement\>) methode

Maakt superscript

```cpp
virtual System::SharedPtr<IMathSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSuperscript(System::SharedPtr<IMathElement> superscript)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Superscript (bovenschrift aan de rechterkant) |

### Retourwaarde

Nieuw wiskundig element van type [IMathSuperscriptElement](../../imathsuperscriptelement/)
## Opmerkingen



Voorbeeld: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto index = System::MakeObject<MathematicalText>(u"4");
auto superscript = element->SetSuperscript(index);
```

## IMathElement::SetSuperscript(System::String) methode


Maakt superscript

```cpp
virtual System::SharedPtr<IMathSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSuperscript(System::String superscript)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| superscript | [System::String](../../../system/string/) | Superscript (bovenschrift aan de rechterkant) |

### Retourwaarde

Nieuw wiskundig element van type [IMathSuperscriptElement](../../imathsuperscriptelement/)
## Opmerkingen



Voorbeeld: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto superscript = element->SetSuperscript(u"4");
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathSuperscriptElement](../../imathsuperscriptelement/)
* Klasse [IMathElement](../)
* Klasse [String](../../../system/string/)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)