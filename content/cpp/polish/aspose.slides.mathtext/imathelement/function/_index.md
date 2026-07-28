---
title: Function()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Przyjmuje funkcję argumentu, używając tej instancji jako nazwy funkcji
type: docs
weight: 53
url: /pl/aspose.slides.mathtext/imathelement/function/
---
## IMathElement::Function(System::SharedPtr\<IMathElement\>) metoda

Przyjmuje funkcję argumentu, używając tej instancji jako nazwy funkcji

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::Function(System::SharedPtr<IMathElement> functionArgument)=0
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| functionArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Argument funkcji |

### Wartość zwracana

Nowy element matematyczny typu [IMathFunction](../../imathfunction/)

## Uwagi



Przykład: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionName->Function(functionArg);
```

## IMathElement::Function(System::String) metoda

Przyjmuje funkcję argumentu, używając tej instancji jako nazwy funkcji

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::Function(System::String functionArgument)=0
```

### Argumenty

| Parameter | Type | Description |
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
* Klasa [IMathElement](../)
* Klasa [String](../../../system/string/)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)