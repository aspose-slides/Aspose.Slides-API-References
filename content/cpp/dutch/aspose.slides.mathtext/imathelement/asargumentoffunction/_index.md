---
title: AsArgumentOfFunction()
second_title: Aspose.Slides voor C++ API-referentie
description: Neemt de opgegeven functie waarbij deze instantie als argument wordt gebruikt
type: docs
weight: 66
url: /nl/aspose.slides.mathtext/imathelement/asargumentoffunction/
---
## IMathElement::AsArgumentOfFunction(System::SharedPtr\<IMathElement\>) methode


Neemt de opgegeven functie waarbij deze instantie als argument wordt gebruikt

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(System::SharedPtr<IMathElement> functionName)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| functionName | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Functienaam |

### Retourwaarde

Nieuw wiskundig element van type [IMathFunction](../../imathfunction/)
## Opmerkingen



Voorbeeld: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(functionName);
```

## IMathElement::AsArgumentOfFunction(System::String) methode


Neemt de opgegeven functie waarbij deze instantie als argument wordt gebruikt

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(System::String functionName)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| functionName | [System::String](../../../system/string/) | Functienaam |

### Retourwaarde

Nieuw wiskundig element van type [IMathFunction](../../imathfunction/)
## Opmerkingen



Voorbeeld: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(u"cos");
```

## IMathElement::AsArgumentOfFunction(MathFunctionsOfOneArgument) methode


Neemt de opgegeven functie waarbij deze instantie als argument wordt gebruikt

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(MathFunctionsOfOneArgument functionType)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| functionType | [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument/) | Een van de algemene functietypen met één argument |

### Retourwaarde

Nieuw wiskundig element van type [IMathFunction](../../imathfunction/)
## Opmerkingen



Voorbeeld: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfOneArgument::ArcSin);
```

## IMathElement::AsArgumentOfFunction(MathFunctionsOfTwoArguments, System::SharedPtr\<IMathElement\>) methode


Neemt de opgegeven functie waarbij deze instantie als argument wordt gebruikt en extra argument opgeeft

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, System::SharedPtr<IMathElement> additionalArgument)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| functionType | [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/) | Een van de algemene functietypen met twee argumenten: Log, Lim, Min, Max |
| additionalArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Aanvullend argument afhankelijk van het type functie |

### Retourwaarde

Nieuw wiskundig element van type [IMathFunction](../../imathfunction/)
## Opmerkingen



Voorbeeld: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto logarithmBase = System::MakeObject<MathematicalText>(u"5");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfTwoArguments::Log, logarithmBase);
// Retourneert de logaritme van 'x' met basis '5'
```

## IMathElement::AsArgumentOfFunction(MathFunctionsOfTwoArguments, System::String) methode


Neemt de opgegeven functie waarbij deze instantie als argument wordt gebruikt en extra argument opgeeft

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, System::String additionalArgument)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| functionType | [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/) | Een van de algemene functietypen met twee argumenten: Log, Lim, Min, Max |
| additionalArgument | [System::String](../../../system/string/) | Aanvullend argument afhankelijk van het type functie |

### Retourwaarde

Nieuw wiskundig element van type [IMathFunction](../../imathfunction/)
## Opmerkingen



Voorbeeld: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfTwoArguments::Log, u"5");
// Retourneert de logaritme van 'x' met basis '5'
```

## Zie ook

* Enum [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument/)
* Enum [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathFunction](../../imathfunction/)
* Klasse [IMathElement](../)
* Klasse [String](../../../system/string/)
* Naamruimte [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)