---
title: MathPhantom()
second_title: Aspose.Slides voor C++ API-referentie
description: Initialiseert een nieuw exemplaar van de MathPhantom-klasse met het opgegeven basis-wiskunde-element.
type: docs
weight: 144
url: /nl/aspose.slides.mathtext/mathphantom/mathphantom/
---
## MathPhantom::MathPhantom(System::SharedPtr\<IMathElement\>) constructor


Initialiseert een nieuw exemplaar van de [MathPhantom](../) klasse met het opgegeven basis wiskunde-element.

```cpp
Aspose::Slides::MathText::MathPhantom::MathPhantom(System::SharedPtr<IMathElement> element)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Het basis [IMathElement](../../imathelement/) waarvan de zichtbaarheid en lay-out worden beheerd door de phantom. Dit element definieert de inhoud die verborgen of getoond kan worden, terwijl het nog steeds invloed heeft op de geometrische uitlijning van de omringende wiskunde. |
## Opmerkingen



Het phantom-element wordt gebruikt om de visuele ruimte van zijn basisuitdrukking te reserveren of te onderdrukken zonder deze noodzakelijkerwijs weer te geven. Het correspondeert met het OMML-element **<m:phant>**. 

Voorbeeld: 
```cpp
System::SharedPtr<IMathElement> fraction = System::MakeObject<MathFraction>(
    System::MakeObject<MathematicalText>(u"1"),
    System::MakeObject<MathematicalText>(u"2"));
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathElement](../../imathelement/)
* Klasse [MathPhantom](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)