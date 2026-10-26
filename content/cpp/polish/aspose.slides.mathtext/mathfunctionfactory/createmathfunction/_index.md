---
title: CreateMathFunction()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Tworzy funkcję matematyczną
type: docs
weight: 1
url: /pl/aspose.slides.mathtext/mathfunctionfactory/createmathfunction/
---
## MathFunctionFactory::CreateMathFunction(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) metoda

Tworzy funkcję matematyczną

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathFunctionFactory::CreateMathFunction(System::SharedPtr<IMathElement> funcName, System::SharedPtr<IMathElement> baseArgument) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| funcName | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Element używany jako nazwa funkcji |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Element używany jako argument funkcji |

### Wartość zwracana

nowa funkcja matematyczna

## MathFunctionFactory::CreateMathFunction(System::String, System::SharedPtr\<IMathElement\>) metoda

Tworzy funkcję matematyczną

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathFunctionFactory::CreateMathFunction(System::String funcName, System::SharedPtr<IMathElement> baseArgument) override
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
* Klasa [MathFunctionFactory](../)
* Klasa [String](../../../system/string/)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)