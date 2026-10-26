---
title: Radical()
second_title: Aspose.Slides voor C++ API-referentie
description: Specificeert de wiskundige wortel van de opgegeven graad uit het opgegeven argument.
type: docs
weight: 131
url: /nl/aspose.slides.mathtext/imathelement/radical/
---
## IMathElement::Radical(System::SharedPtr\<IMathElement\>) methode


Specificeert de wiskundige wortel van de opgegeven graad uit het opgegeven argument.

```cpp
virtual System::SharedPtr<IMathRadical> Aspose::Slides::MathText::IMathElement::Radical(System::SharedPtr<IMathElement> degree)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| degree | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Argument van Radical |

### Retourwaarde

Nieuwe instantie van type [IMathRadical](../../imathradical/)
## Opmerkingen



Voorbeeld: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"2px");
auto degree = System::MakeObject<MathematicalText>(u"y");
auto radical = baseElement->Radical(degree);
```

## IMathElement::Radical(System::String) methode


Specificeert de wiskundige wortel van de opgegeven graad uit het opgegeven argument.

```cpp
virtual System::SharedPtr<IMathRadical> Aspose::Slides::MathText::IMathElement::Radical(System::String degree)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| degree | [System::String](../../../system/string/) | Argument van Radical |

### Retourwaarde

Nieuwe instantie van type [IMathRadical](../../imathradical/)
## Opmerkingen



Voorbeeld: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"2px");
auto radical = baseElement->Radical(u"3");
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathRadical](../../imathradical/)
* Klasse [IMathElement](../)
* Klasse [String](../../../system/string/)
* Naamruimte [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)