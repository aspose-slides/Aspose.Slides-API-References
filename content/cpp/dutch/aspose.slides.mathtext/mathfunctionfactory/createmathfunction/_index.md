---
title: CreateMathFunction()
second_title: Aspose.Slides voor C++ API-referentie
description: Creëert een wiskundige functie
type: docs
weight: 1
url: /nl/aspose.slides.mathtext/mathfunctionfactory/createmathfunction/
---
## MathFunctionFactory::CreateMathFunction(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) method


Creëert een wiskundige functie

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathFunctionFactory::CreateMathFunction(System::SharedPtr<IMathElement> funcName, System::SharedPtr<IMathElement> baseArgument) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| funcName | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Element gebruikt als functienaam |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Element gebruikt als functie-argument |

### Return Value

nieuwe wiskundige functie

## MathFunctionFactory::CreateMathFunction(System::String, System::SharedPtr\<IMathElement\>) method


Creëert een wiskundige functie

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathFunctionFactory::CreateMathFunction(System::String funcName, System::SharedPtr<IMathElement> baseArgument) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| funcName | [System::String](../../../system/string/) | Functienaam |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Element gebruikt als functie-argument |

### Return Value

nieuwe wiskundige functie

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathFunction](../../imathfunction/)
* Klasse [IMathElement](../../imathelement/)
* Klasse [MathFunctionFactory](../)
* Klasse [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)