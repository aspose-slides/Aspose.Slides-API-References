---
title: MathAccent()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een wiskundig accent dat wordt toegepast op een opgegeven wiskundig element met de standaardwaarde voor het accentteken
type: docs
weight: 40
url: /nl/aspose.slides.mathtext/mathaccent/mathaccent/
---
## MathAccent::MathAccent(System::SharedPtr\<IMathElement\>) constructor


Maakt een wiskundig accent dat wordt toegepast op een opgegeven wiskundig element met de standaardwaarde voor het accentteken

```cpp
Aspose::Slides::MathText::MathAccent::MathAccent(System::SharedPtr<IMathElement> element)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | een wiskundig element waarop het accent wordt toegepast |
## Opmerkingen



Voorbeeld: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"x");
auto accent = System::MakeObject<MathAccent>(baseElement);
```

## MathAccent::MathAccent(System::SharedPtr\<IMathElement\>, char16_t) constructor


Maakt een wiskundig accent dat wordt toegepast op een opgegeven wiskundig element

```cpp
Aspose::Slides::MathText::MathAccent::MathAccent(System::SharedPtr<IMathElement> element, char16_t accentCharacter)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | wiskundig element om accent toe te passen |
| accentCharacter | char16_t | accentteken |
## Opmerkingen



Voorbeeld: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"x");
auto accent = System::MakeObject<MathAccent>(baseElement, u'~');
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [MathAccent](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)