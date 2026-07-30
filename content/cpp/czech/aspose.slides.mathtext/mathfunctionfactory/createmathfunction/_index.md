---
title: CreateMathFunction()
second_title: Aspose.Slides pro C++ - referenční dokumentace
description: Vytváří matematickou funkci
type: docs
weight: 1
url: /cs/aspose.slides.mathtext/mathfunctionfactory/createmathfunction/
---
## MathFunctionFactory::CreateMathFunction(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) metoda

Vytváří matematickou funkci

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathFunctionFactory::CreateMathFunction(System::SharedPtr<IMathElement> funcName, System::SharedPtr<IMathElement> baseArgument) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| funcName | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Prvek použitý jako název funkce |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Prvek použitý jako argument funkce |

### Návratová hodnota

nová matematická funkce

## MathFunctionFactory::CreateMathFunction(System::String, System::SharedPtr\<IMathElement\>) metoda

Vytváří matematickou funkci

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathFunctionFactory::CreateMathFunction(System::String funcName, System::SharedPtr<IMathElement> baseArgument) override
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
* Třída [MathFunctionFactory](../)
* Třída [String](../../../system/string/)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)