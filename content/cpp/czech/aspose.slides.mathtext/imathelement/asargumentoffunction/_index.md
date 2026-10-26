---
title: AsArgumentOfFunction()
second_title: Aspose.Slides pro C++ – reference API
description: Použije zadanou funkci s touto instancí jako argument
type: docs
weight: 66
url: /cs/aspose.slides.mathtext/imathelement/asargumentoffunction/
---
## IMathElement::AsArgumentOfFunction(System::SharedPtr\<IMathElement\>) metoda

Použije zadanou funkci s touto instancí jako argument

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(System::SharedPtr<IMathElement> functionName)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| functionName | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Název funkce |

### Návratová hodnota

Nový matematický prvek typu [IMathFunction](../../imathfunction/)
## Poznámky



Příklad: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(functionName);
```

## IMathElement::AsArgumentOfFunction(System::String) metoda

Použije zadanou funkci s touto instancí jako argument

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(System::String functionName)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| functionName | [System::String](../../../system/string/) | Název funkce |

### Návratová hodnota

Nový matematický prvek typu [IMathFunction](../../imathfunction/)
## Poznámky



Příklad: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(u"cos");
```

## IMathElement::AsArgumentOfFunction(MathFunctionsOfOneArgument) metoda

Použije zadanou funkci s touto instancí jako argument

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(MathFunctionsOfOneArgument functionType)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| functionType | [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument/) | Jeden z běžných typů funkcí s jedním argumentem |

### Návratová hodnota

Nový matematický prvek typu [IMathFunction](../../imathfunction/)
## Poznámky



Příklad: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfOneArgument::ArcSin);
```

## IMathElement::AsArgumentOfFunction(MathFunctionsOfTwoArguments, System::SharedPtr\<IMathElement\>) metoda

Použije zadanou funkci s touto instancí jako argument a uvedený další argument

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, System::SharedPtr<IMathElement> additionalArgument)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| functionType | [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/) | Jeden z běžných typů funkcí se dvěma argumenty: Log, Lim, Min, Max |
| additionalArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Další argument v závislosti na typu funkce |

### Návratová hodnota

Nový matematický prvek typu [IMathFunction](../../imathfunction/)
## Poznámky



Příklad: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto logarithmBase = System::MakeObject<MathematicalText>(u"5");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfTwoArguments::Log, logarithmBase);
// Vrací logaritmus 'x' se základnou '5'
```

## IMathElement::AsArgumentOfFunction(MathFunctionsOfTwoArguments, System::String) metoda

Použije zadanou funkci s touto instancí jako argument a uvedený další argument

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, System::String additionalArgument)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| functionType | [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/) | Jeden z běžných typů funkcí se dvěma argumenty: Log, Lim, Min, Max |
| additionalArgument | [System::String](../../../system/string/) | Další argument v závislosti na typu funkce |

### Návratová hodnota

Nový matematický prvek typu [IMathFunction](../../imathfunction/)
## Poznámky



Příklad: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfTwoArguments::Log, u"5");
// Vrací logaritmus 'x' se základnou '5'
```

## Viz také

* Enum [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument/)
* Enum [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IMathFunction](../../imathfunction/)
* Třída [IMathElement](../)
* Třída [String](../../../system/string/)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)