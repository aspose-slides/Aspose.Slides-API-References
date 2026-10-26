---
title: AsArgumentOfFunction()
second_title: Aspose.Slides für C++ API-Referenz
description: Verwendet die angegebene Funktion, wobei diese Instanz als Argument verwendet wird
type: docs
weight: 66
url: /de/aspose.slides.mathtext/imathelement/asargumentoffunction/
---
## IMathElement::AsArgumentOfFunction(System::SharedPtr\<IMathElement\>) Methode

Verwendet die angegebene Funktion, wobei diese Instanz als Argument verwendet wird

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(System::SharedPtr<IMathElement> functionName)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| functionName | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Function name |

### Rückgabewert

New math element of type [IMathFunction](../../imathfunction/)
## Hinweise



Beispiel: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(functionName);
```

## IMathElement::AsArgumentOfFunction(System::String) Methode

Verwendet die angegebene Funktion, wobei diese Instanz als Argument verwendet wird

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(System::String functionName)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| functionName | [System::String](../../../system/string/) | Function name |

### Rückgabewert

New math element of type [IMathFunction](../../imathfunction/)
## Hinweise



Beispiel: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(u"cos");
```

## IMathElement::AsArgumentOfFunction(MathFunctionsOfOneArgument) Methode

Verwendet die angegebene Funktion, wobei diese Instanz als Argument verwendet wird

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(MathFunctionsOfOneArgument functionType)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| functionType | [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument/) | One of the common function type of one argument |

### Rückgabewert

New math element of type [IMathFunction](../../imathfunction/)
## Hinweise



Beispiel: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfOneArgument::ArcSin);
```

## IMathElement::AsArgumentOfFunction(MathFunctionsOfTwoArguments, System::SharedPtr\<IMathElement\>) Methode


Verwendet die angegebene Funktion und den angegebenen zusätzlichen Parameter

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, System::SharedPtr<IMathElement> additionalArgument)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| functionType | [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/) | One of the common function type of two arguments: Log, Lim, Min, Max |
| additionalArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Additional argument depending on the type of function |

### Rückgabewert

New math element of type [IMathFunction](../../imathfunction/)
## Hinweise



Beispiel: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto logarithmBase = System::MakeObject<MathematicalText>(u"5");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfTwoArguments::Log, logarithmBase);
// Gibt den Logarithmus von 'x' zur Basis '5' zurück
```

## IMathElement::AsArgumentOfFunction(MathFunctionsOfTwoArguments, System::String) Methode


Verwendet die angegebene Funktion und den angegebenen zusätzlichen Parameter

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, System::String additionalArgument)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| functionType | [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/) | One of the common function type of two arguments: Log, Lim, Min, Max |
| additionalArgument | [System::String](../../../system/string/) | Additional argument depending on the type of function |

### Rückgabewert

New math element of type [IMathFunction](../../imathfunction/)
## Hinweise



Beispiel: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfTwoArguments::Log, u"5");
// Gibt den Logarithmus von 'x' zur Basis '5' zurück
```

## Siehe auch

* Aufzählung [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument/)
* Aufzählung [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/)
* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathFunction](../../imathfunction/)
* Klasse [IMathElement](../)
* Klasse [String](../../../system/string/)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)