---
title: CreateMathFunction()
second_title: Referencia de la API de Aspose.Slides para C++
description: Crea una función matemática
type: docs
weight: 1
url: /es/aspose.slides.mathtext/mathfunctionfactory/createmathfunction/
---
## MathFunctionFactory::CreateMathFunction(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) método


Crea una función matemática

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathFunctionFactory::CreateMathFunction(System::SharedPtr<IMathElement> funcName, System::SharedPtr<IMathElement> baseArgument) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| funcName | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Elemento usado como nombre de función |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Elemento usado como argumento de la función |

### Valor devuelto

nueva función matemática

## MathFunctionFactory::CreateMathFunction(System::String, System::SharedPtr\<IMathElement\>) método


Crea una función matemática

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathFunctionFactory::CreateMathFunction(System::String funcName, System::SharedPtr<IMathElement> baseArgument) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| funcName | [System::String](../../../system/string/) | Nombre de la función |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Elemento usado como argumento de la función |

### Valor devuelto

nueva función matemática

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathFunction](../../imathfunction/)
* Class [IMathElement](../../imathelement/)
* Class [MathFunctionFactory](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)