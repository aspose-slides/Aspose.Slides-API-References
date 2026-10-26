---
title: Function()
second_title: Aspose.Slides voor C++ API-referentie
description: Neemt een functie van een argument waarbij deze instantie als functienaam wordt gebruikt
type: docs
weight: 53
url: /nl/aspose.slides.mathtext/imathelement/function/
---
## IMathElement::Function(System::SharedPtr\<IMathElement\>) methode


Neemt een functie van een argument waarbij deze instantie als functienaam wordt gebruikt

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::Function(System::SharedPtr<IMathElement> functionArgument)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| functionArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Een argument van de functie |

### Retourwaarde

Nieuw wiskundig element van het type [IMathFunction](../../imathfunction/)
## Opmerkingen



Voorbeeld: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionName->Function(functionArg);
```

## IMathElement::Function(System::String) methode


Neemt een functie van een argument waarbij deze instantie als functienaam wordt gebruikt

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::Function(System::String functionArgument)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| functionArgument | [System::String](../../../system/string/) | Een argument van de functie |

### Retourwaarde

Nieuw wiskundig element van het type [IMathFunction](../../imathfunction/)
## Opmerkingen



Voorbeeld: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto func = functionName->Function(u"x");
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathFunction](../../imathfunction/)
* Klasse [IMathElement](../)
* Klasse [String](../../../system/string/)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)