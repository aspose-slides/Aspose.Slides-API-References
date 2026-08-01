---
title: MathArray()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een wiskundige array aan en plaatst het opgegeven element erin
type: docs
weight: 144
url: /nl/aspose.slides.mathtext/matharray/matharray/
---
## MathArray::MathArray(System::SharedPtr\<IMathElement\>) constructor


Maakt een wiskundige array aan en plaatst het opgegeven element erin

```cpp
Aspose::Slides::MathText::MathArray::MathArray(System::SharedPtr<IMathElement> element)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Het element om in de array te plaatsen |
## Opmerkingen



Voorbeeld: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
```

## MathArray::MathArray(System::SharedPtr\<System::Collections::Generic::IEnumerable\<System::SharedPtr\<IMathElement\>\>\>) constructor


Maakt een wiskundige array aan en plaatst de opgegeven elementen erin

```cpp
Aspose::Slides::MathText::MathArray::MathArray(System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<IMathElement>>> elements)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| elements | [System::SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\>\>\> | Elementen om in de array te plaatsen |

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathElement](../../imathelement/)
* Klasse [MathArray](../)
* Klasse [IEnumerable](../../../system.collections.generic/ienumerable/)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)