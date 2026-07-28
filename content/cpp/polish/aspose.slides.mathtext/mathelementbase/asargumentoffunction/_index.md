---
title: AsArgumentOfFunction()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Przyjmuje określoną funkcję, używając tej instancji jako argumentu
type: docs
weight: 53
url: /pl/aspose.slides.mathtext/mathelementbase/asargumentoffunction/
---
## MathElementBase::AsArgumentOfFunction(System::SharedPtr\<IMathElement\>) metoda

Przyjmuje określoną funkcję, używając tej instancji jako argumentu

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(System::SharedPtr<IMathElement> functionName) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| functionName | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Nazwa funkcji |

### Wartość zwracana

Nowy element matematyczny typu [IMathFunction](../../imathfunction/)

## Uwagi


Przykład: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(functionName);
```

## MathElementBase::AsArgumentOfFunction(System::String) metoda

Przyjmuje określoną funkcję, używając tej instancji jako argumentu

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(System::String functionName) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| functionName | [System::String](../../../system/string/) | Nazwa funkcji |

### Wartość zwracana

Nowy element matematyczny typu [IMathFunction](../../imathfunction/)

## Uwagi


Przykład: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(u"cos");
```

## MathElementBase::AsArgumentOfFunction(MathFunctionsOfOneArgument) metoda

Przyjmuje określoną funkcję, używając tej instancji jako argumentu

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(MathFunctionsOfOneArgument functionType) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| functionType | [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument/) | Jeden z typowych typów funkcji jednego argumentu |

### Wartość zwracana

Nowy element matematyczny typu [IMathFunction](../../imathfunction/)

## Uwagi


Przykład: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(functionName);
```

## MathElementBase::AsArgumentOfFunction(MathFunctionsOfTwoArguments, System::SharedPtr\<IMathElement\>) metoda

Przyjmuje określoną funkcję, używając tej instancji jako argumentu oraz dodatkowy argument

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, System::SharedPtr<IMathElement> additionalArgument) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| functionType | [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/) | Jeden z typowych typów funkcji dwóch argumentów: Log, Lim, Min, Max |
| additionalArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Dodatkowy argument zależny od typu funkcji |

### Wartość zwracana

Nowy element matematyczny typu [IMathFunction](../../imathfunction/)

## Uwagi


Przykład: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto logarithmBase = System::MakeObject<MathematicalText>(u"5");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfTwoArguments::Log, logarithmBase);
// Zwraca logarytm 'x' o podstawie '5'
```

## MathElementBase::AsArgumentOfFunction(MathFunctionsOfTwoArguments, System::String) metoda

Przyjmuje określoną funkcję, używając tej instancji jako argumentu oraz dodatkowy argument

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, System::String additionalArgument) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| functionType | [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/) | Jeden z typowych typów funkcji dwóch argumentów: Log, Lim, Min, Max |
| additionalArgument | [System::String](../../../system/string/) | Dodatkowy argument zależny od typu funkcji |

### Wartość zwracana

Nowy element matematyczny typu [IMathFunction](../../imathfunction/)

## Uwagi


Przykład: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfTwoArguments::Log, u"5");
// Zwraca logarytm 'x' o podstawie '5'
```

## Zobacz także

* Enum [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument/)
* Enum [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathFunction](../../imathfunction/)
* Klasa [IMathElement](../../imathelement/)
* Klasa [MathElementBase](../)
* Klasa [String](../../../system/string/)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)