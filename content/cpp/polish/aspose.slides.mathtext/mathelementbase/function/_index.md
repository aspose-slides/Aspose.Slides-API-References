---
title: Function()
second_title: Aspose.Slides dla C++ referencja API
description: Przyjmuje funkcję argumentu używając tej instancji jako nazwy funkcji
type: docs
weight: 40
url: /pl/aspose.slides.mathtext/mathelementbase/function/
---
## MathElementBase::Function(System::SharedPtr\<IMathElement\>) metoda


Przyjmuje funkcję argumentu, używając tej instancji jako nazwy funkcji

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::Function(System::SharedPtr<IMathElement> functionArgument) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| functionArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Argument funkcji |

### Wartość zwracana

Nowy element matematyczny typu [IMathFunction](../../imathfunction/)
## Uwagi



Przykład: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionName->Function(functionArg);
```

## MathElementBase::Function(System::String) metoda


Przyjmuje funkcję argumentu, używając tej instancji jako nazwy funkcji

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::Function(System::String functionArgument) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| functionArgument | [System::String](../../../system/string/) | Argument funkcji |

### Wartość zwracana

Nowy element matematyczny typu [IMathFunction](../../imathfunction/)
## Uwagi



Przykład: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto func = functionName->Function(u"x");
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathFunction](../../imathfunction/)
* Klasa [IMathElement](../../imathelement/)
* Klasa [MathElementBase](../)
* Klasa [String](../../../system/string/)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)