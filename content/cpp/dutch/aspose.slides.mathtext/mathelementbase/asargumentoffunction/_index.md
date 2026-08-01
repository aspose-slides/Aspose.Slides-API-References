---
title: AsArgumentOfFunction()
second_title: Aspose.Slides voor C++ API-referentie
description: Neemt de opgegeven functie waarbij dit exemplaar als argument wordt gebruikt
type: docs
weight: 53
url: /nl/aspose.slides.mathtext/mathelementbase/asargumentoffunction/
---
## MathElementBase::AsArgumentOfFunction(System::SharedPtr\<IMathElement\>) methode

Neemt de opgegeven functie waarbij dit exemplaar als argument wordt gebruikt

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(System::SharedPtr<IMathElement> functionName) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| functionName | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Functienaam |

### Retourwaarde

Nieuw wiskundig element van type [IMathFunction](../../imathfunction/)
## Opmerkingen



Voorbeeld: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(functionName);
```

## MathElementBase::AsArgumentOfFunction(System::String) methode

Neemt de opgegeven functie waarbij dit exemplaar als argument wordt gebruikt

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(System::String functionName) override
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

## MathElementBase::AsArgumentOfFunction(MathFunctionsOfOneArgument) methode

Neemt de opgegeven functie waarbij dit exemplaar als argument wordt gebruikt

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(MathFunctionsOfOneArgument functionType) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| functionType | [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument/) | Een van de gemeenschappelijke functietypen van één argument |

### Retourwaarde

Nieuw wiskundig element van type [IMathFunction](../../imathfunction/)
## Opmerkingen



Voorbeeld: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(functionName);
```

## MathElementBase::AsArgumentOfFunction(MathFunctionsOfTwoArguments, System::SharedPtr\<IMathElement\>) methode

Neemt de opgegeven functie waarbij dit exemplaar als argument wordt gebruikt en een opgegeven extra argument

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, System::SharedPtr<IMathElement> additionalArgument) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| functionType | [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/) | Een van de gemeenschappelijke functietypen van twee argumenten: Log, Lim, Min, Max |
| additionalArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Extra argument afhankelijk van het type functie |

### Retourwaarde

Nieuw wiskundig element van type [IMathFunction](../../imathfunction/)
## Opmerkingen



Voorbeeld: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto logarithmBase = System::MakeObject<MathematicalText>(u"5");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfTwoArguments::Log, logarithmBase);
// Retourneert de logaritme van 'x' naar het grondtal '5'
```

## MathElementBase::AsArgumentOfFunction(MathFunctionsOfTwoArguments, System::String) methode

Neemt de opgegeven functie waarbij dit exemplaar als argument wordt gebruikt en een opgegeven extra argument

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, System::String additionalArgument) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| functionType | [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/) | Een van de gemeenschappelijke functietypen van twee argumenten: Log, Lim, Min, Max |
| additionalArgument | [System::String](../../../system/string/) | Extra argument afhankelijk van het type functie |

### Retourwaarde

Nieuw wiskundig element van type [IMathFunction](../../imathfunction/)
## Opmerkingen



Voorbeeld: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfTwoArguments::Log, u"5");
// Retourneert de logaritme van 'x' naar het grondtal '5'
```

## Zie ook

* Enum [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument/)
* Enum [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathFunction](../../imathfunction/)
* Klasse [IMathElement](../../imathelement/)
* Klasse [MathElementBase](../)
* Klasse [String](../../../system/string/)
* Naamruimte [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)