---
title: CreateMathFunction()
second_title: Aspose.Slides para C++ Referência da API
description: Cria função matemática
type: docs
weight: 1
url: /pt/aspose.slides.mathtext/imathfunctionfactory/createmathfunction/
---
## IMathFunctionFactory::CreateMathFunction(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) method


Cria função matemática

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathFunctionFactory::CreateMathFunction(System::SharedPtr<IMathElement> funcName, System::SharedPtr<IMathElement> baseArgument)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| funcName | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Elemento usado como nome da função |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Elemento usado como argumento da função |

### Valor de Retorno

nova função matemática

## IMathFunctionFactory::CreateMathFunction(System::String, System::SharedPtr\<IMathElement\>) method


Cria função matemática

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathFunctionFactory::CreateMathFunction(System::String funcName, System::SharedPtr<IMathElement> baseArgument)=0
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
* Classe [IMathFunctionFactory](../)
* Classe [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)