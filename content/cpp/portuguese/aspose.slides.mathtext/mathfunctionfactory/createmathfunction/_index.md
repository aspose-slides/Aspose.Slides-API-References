---
title: CreateMathFunction()
second_title: Referência da API Aspose.Slides for C++
description: Cria função matemática
type: docs
weight: 1
url: /pt/aspose.slides.mathtext/mathfunctionfactory/createmathfunction/
---
## MathFunctionFactory::CreateMathFunction(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) método

Cria função matemática

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathFunctionFactory::CreateMathFunction(System::SharedPtr<IMathElement> funcName, System::SharedPtr<IMathElement> baseArgument) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| funcName | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Elemento usado como nome da função |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Elemento usado como argumento da função |

### Valor de Retorno

nova função matemática

## MathFunctionFactory::CreateMathFunction(System::String, System::SharedPtr\<IMathElement\>) método

Cria função matemática

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathFunctionFactory::CreateMathFunction(System::String funcName, System::SharedPtr<IMathElement> baseArgument) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| funcName | [System::String](../../../system/string/) | Nome da função |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Elemento usado como argumento da função |

### Valor de Retorno

nova função matemática

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathFunction](../../imathfunction/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathFunctionFactory](../)
* Classe [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)