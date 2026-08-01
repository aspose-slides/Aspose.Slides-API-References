---
title: SetSuperscript()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt superscript
type: docs
weight: 79
url: /nl/aspose.slides.mathtext/mathelementbase/setsuperscript/
---
## MathElementBase::SetSuperscript(System::SharedPtr\<IMathElement\>) methode


Creëert superscript

```cpp
System::SharedPtr<IMathSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSuperscript(System::SharedPtr<IMathElement> superscript) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Superscript (bovenschrift aan de rechterkant) |

### Retourwaarde

Nieuw wiskundig element van type [IMathSuperscriptElement](../../imathsuperscriptelement/)
## Opmerkingen



Voorbeeld: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto index = System::MakeObject<MathematicalText>(u"4");
auto superscript = element->SetSuperscript(index);
```

## MathElementBase::SetSuperscript(System::String) methode


Creëert superscript

```cpp
System::SharedPtr<IMathSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSuperscript(System::String superscript) override
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
* Klasse [IMathElement](../../imathelement/)
* Klasse [MathElementBase](../)
* Klasse [String](../../../system/string/)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)