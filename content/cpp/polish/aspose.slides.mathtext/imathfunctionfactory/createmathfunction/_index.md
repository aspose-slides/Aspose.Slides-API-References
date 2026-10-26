---
title: CreateMathFunction()
second_title: Referencja API Aspose.Slides dla C++
description: Tworzy funkcję matematyczną
type: docs
weight: 1
url: /pl/aspose.slides.mathtext/imathfunctionfactory/createmathfunction/
---
## IMathFunctionFactory::CreateMathFunction(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) metoda

Tworzy funkcję matematyczną

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathFunctionFactory::CreateMathFunction(System::SharedPtr<IMathElement> funcName, System::SharedPtr<IMathElement> baseArgument)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| funcName | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Element używany jako nazwa funkcji |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Element używany jako argument funkcji |

### Wartość zwracana

nowa funkcja matematyczna

## IMathFunctionFactory::CreateMathFunction(System::String, System::SharedPtr\<IMathElement\>) metoda

Tworzy funkcję matematyczną

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathFunctionFactory::CreateMathFunction(System::String funcName, System::SharedPtr<IMathElement> baseArgument)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| funcName | [System::String](../../../system/string/) | Nazwa funkcji |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Element używany jako argument funkcji |

### Wartość zwracana

nowa funkcja matematyczna

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathFunction](../../imathfunction/)
* Klasa [IMathElement](../../imathelement/)
* Klasa [IMathFunctionFactory](../)
* Klasa [String](../../../system/string/)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)