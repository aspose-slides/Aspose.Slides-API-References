---
title: Radical()
second_title: Aspose.Slides voor C++ API-referentie
description: Specificeert de wiskundige wortel van de opgegeven graad van het gespecificeerde argument.
type: docs
weight: 118
url: /nl/aspose.slides.mathtext/mathelementbase/radical/
---
## MathElementBase::Radical(System::SharedPtr\<IMathElement\>) methode


Specificeert de wiskundige wortel van de opgegeven graad van het gespecificeerde argument.

```cpp
System::SharedPtr<IMathRadical> Aspose::Slides::MathText::MathElementBase::Radical(System::SharedPtr<IMathElement> degree) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| degree | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Argument van Radical |

### Retourwaarde

Nieuwe instantie van type [IMathRadical](../../imathradical/)

## Opmerkingen



Voorbeeld: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"2px");
auto degree = System::MakeObject<MathematicalText>(u"y");
auto radical = baseElement->Radical(degree);
```

## MathElementBase::Radical(System::String) methode


Specificeert de wiskundige wortel van de opgegeven graad van het gespecificeerde argument.

```cpp
System::SharedPtr<IMathRadical> Aspose::Slides::MathText::MathElementBase::Radical(System::String degree) override
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
* Klasse [IMathElement](../../imathelement/)
* Klasse [MathElementBase](../)
* Klasse [String](../../../system/string/)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)