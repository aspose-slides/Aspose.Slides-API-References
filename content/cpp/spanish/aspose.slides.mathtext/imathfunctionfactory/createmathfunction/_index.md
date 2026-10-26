---
title: CreateMathFunction()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea una función matemática
type: docs
weight: 1
url: /es/aspose.slides.mathtext/imathfunctionfactory/createmathfunction/
---
## IMathFunctionFactory::CreateMathFunction(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) método

Crea una función matemática

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathFunctionFactory::CreateMathFunction(System::SharedPtr<IMathElement> funcName, System::SharedPtr<IMathElement> baseArgument)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| funcName | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Elemento usado como nombre de la función |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Elemento usado como argumento de la función |

### Valor de retorno

nueva función matemática

## IMathFunctionFactory::CreateMathFunction(System::String, System::SharedPtr\<IMathElement\>) método

Crea una función matemática

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathFunctionFactory::CreateMathFunction(System::String funcName, System::SharedPtr<IMathElement> baseArgument)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| funcName | [System::String](../../../system/string/) | Nombre de la función |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Elemento usado como argumento de la función |

### Valor de retorno

nueva función matemática

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IMathFunction](../../imathfunction/)
* Clase [IMathElement](../../imathelement/)
* Clase [IMathFunctionFactory](../)
* Clase [String](../../../system/string/)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)