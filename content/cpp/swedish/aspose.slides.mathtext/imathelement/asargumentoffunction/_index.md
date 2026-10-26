---
title: AsArgumentOfFunction()
second_title: Aspose.Slides för C++ API-referens
description: Tar angiven funktion och använder denna instans som argument
type: docs
weight: 66
url: /sv/aspose.slides.mathtext/imathelement/asargumentoffunction/
---
## IMathElement::AsArgumentOfFunction(System::SharedPtr\<IMathElement\>) metod


Tar den angivna funktionen och använder denna instans som argument

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(System::SharedPtr<IMathElement> functionName)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| functionName | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Funktionsnamn |

### Returvärde

Ny matematikelement av typen [IMathFunction](../../imathfunction/)
## Anmärkningar



Exempel: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(functionName);
```

## IMathElement::AsArgumentOfFunction(System::String) metod


Tar den angivna funktionen och använder denna instans som argument

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(System::String functionName)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| functionName | [System::String](../../../system/string/) | Funktionsnamn |

### Returvärde

Ny matematikelement av typen [IMathFunction](../../imathfunction/)
## Anmärkningar



Exempel: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(u"cos");
```

## IMathElement::AsArgumentOfFunction(MathFunctionsOfOneArgument) metod


Tar den angivna funktionen och använder denna instans som argument

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(MathFunctionsOfOneArgument functionType)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| functionType | [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument/) | En av de vanliga funktionstyperna för ett argument |

### Returvärde

Ny matematikelement av typen [IMathFunction](../../imathfunction/)
## Anmärkningar



Exempel: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfOneArgument::ArcSin);
```

## IMathElement::AsArgumentOfFunction(MathFunctionsOfTwoArguments, System::SharedPtr\<IMathElement\>) metod


Tar den angivna funktionen och använder denna instans som argument samt angivet ytterligare argument

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, System::SharedPtr<IMathElement> additionalArgument)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| functionType | [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/) | En av de vanliga funktionstyperna för två argument: Log, Lim, Min, Max |
| additionalArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Ytterligare argument beroende på funktionens typ |

### Returvärde

Ny matematikelement av typen [IMathFunction](../../imathfunction/)
## Anmärkningar



Exempel: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto logarithmBase = System::MakeObject<MathematicalText>(u"5");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfTwoArguments::Log, logarithmBase);
// Returnerar logaritmen av 'x' till basen '5'
```

## IMathElement::AsArgumentOfFunction(MathFunctionsOfTwoArguments, System::String) metod


Tar den angivna funktionen och använder denna instans som argument samt angivet ytterligare argument

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, System::String additionalArgument)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| functionType | [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/) | En av de vanliga funktionstyperna för två argument: Log, Lim, Min, Max |
| additionalArgument | [System::String](../../../system/string/) | Ytterligare argument beroende på funktionens typ |

### Returvärde

Ny matematikelement av typen [IMathFunction](../../imathfunction/)
## Anmärkningar



Exempel: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfTwoArguments::Log, u"5");
// Returnerar logaritmen av 'x' till basen '5'
```

## Se också

* Enum [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument/)
* Enum [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IMathFunction](../../imathfunction/)
* Klass [IMathElement](../)
* Klass [String](../../../system/string/)
* Namnrymd [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)