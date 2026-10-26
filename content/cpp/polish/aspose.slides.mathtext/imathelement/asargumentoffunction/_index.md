---
title: AsArgumentOfFunction()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Używa określonej funkcji, przyjmując tę instancję jako argument
type: docs
weight: 66
url: /pl/aspose.slides.mathtext/imathelement/asargumentoffunction/
---
## IMathElement::AsArgumentOfFunction(System::SharedPtr\<IMathElement\>) metoda

Używa określonej funkcji, przyjmując tę instancję jako argument

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(System::SharedPtr<IMathElement> functionName)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| functionName | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Nazwa funkcji |

### Wartość zwracana

Nowy element matematyczny typu [IMathFunction](../../imathfunction/)

## Uwagi

Przykład: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(functionName);
```

## IMathElement::AsArgumentOfFunction(System::String) metoda

Używa określonej funkcji, przyjmując tę instancję jako argument

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(System::String functionName)=0
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

## IMathElement::AsArgumentOfFunction(MathFunctionsOfOneArgument) metoda

Używa określonej funkcji, przyjmując tę instancję jako argument

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(MathFunctionsOfOneArgument functionType)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| functionType | [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument/) | Jedna z typowych funkcji jednego argumentu |

### Wartość zwracana

Nowy element matematyczny typu [IMathFunction](../../imathfunction/)

## Uwagi

Przykład: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfOneArgument::ArcSin);
```

## IMathElement::AsArgumentOfFunction(MathFunctionsOfTwoArguments, System::SharedPtr\<IMathElement\>) metoda

Używa określonej funkcji, przyjmując tę instancję jako argument i dodatkowy argument

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, System::SharedPtr<IMathElement> additionalArgument)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| functionType | [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/) | Jedna z powszechnych funkcji dwóch argumentów: Log, Lim, Min, Max |
| additionalArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Dodatkowy argument zależny od typu funkcji |

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

## IMathElement::AsArgumentOfFunction(MathFunctionsOfTwoArguments, System::String) metoda

Używa określonej funkcji, przyjmując tę instancję jako argument i dodatkowy argument

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, System::String additionalArgument)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| functionType | [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/) | Jedna z powszechnych funkcji dwóch argumentów: Log, Lim, Min, Max |
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
* Klasa [IMathElement](../)
* Klasa [String](../../../system/string/)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)