---
title: AsArgumentOfFunction()
second_title: Aspose.Slides für C++ API-Referenz
description: Verwendet die angegebene Funktion und nutzt diese Instanz als Argument
type: docs
weight: 53
url: /de/aspose.slides.mathtext/mathelementbase/asargumentoffunction/
---
## MathElementBase::AsArgumentOfFunction(System::SharedPtr\<IMathElement\>) Methode


Verwendet die angegebene Funktion und nutzt diese Instanz als Argument

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(System::SharedPtr<IMathElement> functionName) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| functionName | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Funktionsname |

### Rückgabewert

Neues mathematisches Element vom Typ [IMathFunction](../../imathfunction/)
## Anmerkungen



Beispiel: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(functionName);
```

## MathElementBase::AsArgumentOfFunction(System::String) Methode


Verwendet die angegebene Funktion und nutzt diese Instanz als Argument

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(System::String functionName) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| functionName | [System::String](../../../system/string/) | Funktionsname |

### Rückgabewert

Neues mathematisches Element vom Typ [IMathFunction](../../imathfunction/)
## Anmerkungen



Beispiel: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(u"cos");
```

## MathElementBase::AsArgumentOfFunction(MathFunctionsOfOneArgument) Methode


Verwendet die angegebene Funktion und nutzt diese Instanz als Argument

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(MathFunctionsOfOneArgument functionType) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| functionType | [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument/) | Einer der gängigen Funktionstypen mit einem Argument |

### Rückgabewert

Neues mathematisches Element vom Typ [IMathFunction](../../imathfunction/)
## Anmerkungen



Beispiel: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(functionName);
```

## MathElementBase::AsArgumentOfFunction(MathFunctionsOfTwoArguments, System::SharedPtr\<IMathElement\>) Methode


Verwendet die angegebene Funktion und nutzt diese Instanz als Argument und den angegebenen zusätzlichen Parameter

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, System::SharedPtr<IMathElement> additionalArgument) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| functionType | [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/) | Einer der gängigen Funktionstypen mit zwei Argumenten: Log, Lim, Min, Max |
| additionalArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Zusätzliches Argument, abhängig vom Funktionstyp |

### Rückgabewert

Neues mathematisches Element vom Typ [IMathFunction](../../imathfunction/)
## Anmerkungen



Beispiel: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto logarithmBase = System::MakeObject<MathematicalText>(u"5");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfTwoArguments::Log, logarithmBase);
// Gibt den Logarithmus von 'x' zur Basis '5' zurück
```

## MathElementBase::AsArgumentOfFunction(MathFunctionsOfTwoArguments, System::String) Methode


Verwendet die angegebene Funktion und nutzt diese Instanz als Argument und den angegebenen zusätzlichen Parameter

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, System::String additionalArgument) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| functionType | [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/) | Einer der gängigen Funktionstypen mit zwei Argumenten: Log, Lim, Min, Max |
| additionalArgument | [System::String](../../../system/string/) | Zusätzliches Argument, abhängig vom Funktionstyp |

### Rückgabewert

Neues mathematisches Element vom Typ [IMathFunction](../../imathfunction/)
## Anmerkungen



Beispiel: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfTwoArguments::Log, u"5");
// Gibt den Logarithmus von 'x' zur Basis '5' zurück
```

## Siehe auch

* Enum [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument/)
* Enum [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathFunction](../../imathfunction/)
* Class [IMathElement](../../imathelement/)
* Class [MathElementBase](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)