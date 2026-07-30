---
title: CreateMathFunction()
second_title: Aspose.Slides pro C++ API Reference
description: Vytvoří matematickou funkci
type: docs
weight: 1
url: /cs/aspose.slides.mathtext/imathfunctionfactory/createmathfunction/
---
## IMathFunctionFactory::CreateMathFunction(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) metoda

Vytvoří matematickou funkci

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathFunctionFactory::CreateMathFunction(System::SharedPtr<IMathElement> funcName, System::SharedPtr<IMathElement> baseArgument)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| funcName | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Prvek použitý jako název funkce |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Prvek použitý jako argument funkce |

### Návratová hodnota

nová matematická funkce

## IMathFunctionFactory::CreateMathFunction(System::String, System::SharedPtr\<IMathElement\>) metoda

Vytvoří matematickou funkci

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathFunctionFactory::CreateMathFunction(System::String funcName, System::SharedPtr<IMathElement> baseArgument)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| funcName | [System::String](../../../system/string/) | Název funkce |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Prvek použitý jako argument funkce |

### Návratová hodnota

nová matematická funkce

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IMathFunction](../../imathfunction/)
* Třída [IMathElement](../../imathelement/)
* Třída [IMathFunctionFactory](../)
* Třída [String](../../../system/string/)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)