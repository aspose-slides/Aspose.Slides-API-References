---
title: Function()
second_title: Aspose.Slides voor C++ API-referentie
description: Neemt een functie van een argument waarbij dit exemplaar als functienaam wordt gebruikt
type: docs
weight: 40
url: /nl/aspose.slides.mathtext/mathelementbase/function/
---
## MathElementBase::Function(System::SharedPtr\<IMathElement\>) methode


Neemt een functie van een argument waarbij dit exemplaar als functienaam wordt gebruikt

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::Function(System::SharedPtr<IMathElement> functionArgument) override
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| functionArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Een argument van de functie |

### Retourwaarde

Nieuw wiskundig element van type [IMathFunction](../../imathfunction/)
## Opmerkingen



Voorbeeld: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionName->Function(functionArg);
```

## MathElementBase::Function(System::String) methode


Neemt een functie van een argument waarbij dit exemplaar als functienaam wordt gebruikt

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::Function(System::String functionArgument) override
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| functionArgument | [System::String](../../../system/string/) | Een argument van de functie |

### Retourwaarde

Nieuw wiskundig element van type [IMathFunction](../../imathfunction/)
## Opmerkingen



Voorbeeld: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto func = functionName->Function(u"x");
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathFunction](../../imathfunction/)
* Klasse [IMathElement](../../imathelement/)
* Klasse [MathElementBase](../)
* Klasse [String](../../../system/string/)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)