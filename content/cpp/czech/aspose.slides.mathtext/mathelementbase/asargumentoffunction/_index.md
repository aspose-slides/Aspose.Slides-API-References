---
title: AsArgumentOfFunction()
second_title: Aspose.Slides pro C++ – reference API
description: Použije zadanou funkci s tímto objektem jako argument
type: docs
weight: 53
url: /cs/aspose.slides.mathtext/mathelementbase/asargumentoffunction/
---
## MathElementBase::AsArgumentOfFunction(System::SharedPtr\<IMathElement\>) metoda


Použije zadanou funkci s tímto objektem jako argument

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(System::SharedPtr<IMathElement> functionName) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| functionName | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Název funkce |

### Návratová hodnota

Nový matematický prvek typu [IMathFunction](../../imathfunction/)
## Poznámky



Příklad: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(functionName);
```

## MathElementBase::AsArgumentOfFunction(System::String) metoda


Použije zadanou funkci s tímto objektem jako argument

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(System::String functionName) override
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

## MathElementBase::AsArgumentOfFunction(MathFunctionsOfOneArgument) metoda


Použije zadanou funkci s tímto objektem jako argument

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(MathFunctionsOfOneArgument functionType) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| functionType | [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument/) | Jedna z běžných typů funkcí s jedním argumentem |

### Návratová hodnota

Nový matematický prvek typu [IMathFunction](../../imathfunction/)
## Poznámky



Příklad: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(functionName);
```

## MathElementBase::AsArgumentOfFunction(MathFunctionsOfTwoArguments, System::SharedPtr\<IMathElement\>) metoda


Použije zadanou funkci s tímto objektem jako argument a určený další argument

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, System::SharedPtr<IMathElement> additionalArgument) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| functionType | [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/) | Jedna z běžných typů funkcí se dvěma argumenty: Log, Lim, Min, Max |
| additionalArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Další argument v závislosti na typu funkce |

### Návratová hodnota

Nový matematický prvek typu [IMathFunction](../../imathfunction/)
## Poznámky



Příklad: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto logarithmBase = System::MakeObject<MathematicalText>(u"5");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfTwoArguments::Log, logarithmBase);
// Vrací logaritmus 'x' se základem '5'
```

## MathElementBase::AsArgumentOfFunction(MathFunctionsOfTwoArguments, System::String) metoda


Použije zadanou funkci s tímto objektem jako argument a určený další argument

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, System::String additionalArgument) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| functionType | [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/) | Jedna z běžných typů funkcí se dvěma argumenty: Log, Lim, Min, Max |
| additionalArgument | [System::String](../../../system/string/) | Další argument v závislosti na typu funkce |

### Návratová hodnota

Nový matematický prvek typu [IMathFunction](../../imathfunction/)
## Poznámky



Příklad: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfTwoArguments::Log, u"5");
// Vrací logaritmus 'x' se základem '5'
```

## Viz také

* Enum [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument/)
* Enum [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* třída [IMathFunction](../../imathfunction/)
* třída [IMathElement](../../imathelement/)
* třída [MathElementBase](../)
* třída [String](../../../system/string/)
* jmenný prostor [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)