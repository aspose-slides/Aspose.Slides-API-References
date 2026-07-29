---
title: AsArgumentOfFunction()
second_title: Aspose.Slides för C++ API-referens
description: Tar den angivna funktionen och använder detta objekt som argument
type: docs
weight: 53
url: /sv/aspose.slides.mathtext/mathelementbase/asargumentoffunction/
---
## MathElementBase::AsArgumentOfFunction(System::SharedPtr\<IMathElement\>) metod

Tar den angivna funktionen och använder detta objekt som argument

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(System::SharedPtr<IMathElement> functionName) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| functionName | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Funktionsnamn |

### Returvärde

Nytt matematiskt element av typen [IMathFunction](../../imathfunction/)

## Anmärkningar

Exempel: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(functionName);
```

## MathElementBase::AsArgumentOfFunction(System::String) metod

Tar den angivna funktionen och använder detta objekt som argument

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(System::String functionName) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| functionName | [System::String](../../../system/string/) | Funktionsnamn |

### Returvärde

Nytt matematiskt element av typen [IMathFunction](../../imathfunction/)

## Anmärkningar

Exempel: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(u"cos");
```

## MathElementBase::AsArgumentOfFunction(MathFunctionsOfOneArgument) metod

Tar den angivna funktionen och använder detta objekt som argument

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(MathFunctionsOfOneArgument functionType) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| functionType | [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument/) | En av de vanliga funktionstyperna för ett argument |

### Returvärde

Nytt matematiskt element av typen [IMathFunction](../../imathfunction/)

## Anmärkningar

Exempel: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(functionName);
```

## MathElementBase::AsArgumentOfFunction(MathFunctionsOfTwoArguments, System::SharedPtr\<IMathElement\>) metod

Tar den angivna funktionen och använder detta objekt som argument och angivet ytterligare argument

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, System::SharedPtr<IMathElement> additionalArgument) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| functionType | [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/) | En av de vanliga funktionstyperna för två argument: Log, Lim, Min, Max |
| additionalArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Ytterligare argument beroende på funktionstypen |

### Returvärde

Nytt matematiskt element av typen [IMathFunction](../../imathfunction/)

## Anmärkningar

Exempel: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto logarithmBase = System::MakeObject<MathematicalText>(u"5");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfTwoArguments::Log, logarithmBase);
// Returnerar logaritmen av 'x' till basen '5'
```

## MathElementBase::AsArgumentOfFunction(MathFunctionsOfTwoArguments, System::String) metod

Tar den angivna funktionen och använder detta objekt som argument och angivet ytterligare argument

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, System::String additionalArgument) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| functionType | [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/) | En av de vanliga funktionstyperna för två argument: Log, Lim, Min, Max |
| additionalArgument | [System::String](../../../system/string/) | Ytterligare argument beroende på funktionstypen |

### Returvärde

Nytt matematiskt element av typen [IMathFunction](../../imathfunction/)

## Anmärkningar

Exempel: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfTwoArguments::Log, u"5");
// Returnerar logaritmen av 'x' till basen '5'
```

## Se även

* Enum [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument/)
* Enum [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IMathFunction](../../imathfunction/)
* Klass [IMathElement](../../imathelement/)
* Klass [MathElementBase](../)
* Klass [String](../../../system/string/)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)