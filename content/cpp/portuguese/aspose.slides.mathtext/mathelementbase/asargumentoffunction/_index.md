---
title: AsArgumentOfFunction()
second_title: Aspose.Slides para C++ Referência da API
description: Utiliza a função especificada usando esta instância como argumento
type: docs
weight: 53
url: /pt/aspose.slides.mathtext/mathelementbase/asargumentoffunction/
---
## MathElementBase::AsArgumentOfFunction(System::SharedPtr\<IMathElement\>) método

Utiliza a função especificada usando esta instância como argumento

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(System::SharedPtr<IMathElement> functionName) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| functionName | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Nome da função |

### Valor de retorno

Novo elemento matemático do tipo [IMathFunction](../../imathfunction/)

## Observações

Exemplo: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(functionName);
```

## MathElementBase::AsArgumentOfFunction(System::String) método

Utiliza a função especificada usando esta instância como argumento

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(System::String functionName) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| functionName | [System::String](../../../system/string/) | Nome da função |

### Valor de retorno

Novo elemento matemático do tipo [IMathFunction](../../imathfunction/)

## Observações

Exemplo: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(u"cos");
```

## MathElementBase::AsArgumentOfFunction(MathFunctionsOfOneArgument) método

Utiliza a função especificada usando esta instância como argumento

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(MathFunctionsOfOneArgument functionType) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| functionType | [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument/) | Um dos tipos de função comuns de um argumento |

### Valor de retorno

Novo elemento matemático do tipo [IMathFunction](../../imathfunction/)

## Observações

Exemplo: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(functionName);
```

## MathElementBase::AsArgumentOfFunction(MathFunctionsOfTwoArguments, System::SharedPtr\<IMathElement\>) método

Utiliza a função especificada usando esta instância como argumento e o argumento adicional especificado

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, System::SharedPtr<IMathElement> additionalArgument) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| functionType | [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/) | Um dos tipos de função comuns de dois argumentos: Log, Lim, Min, Max |
| additionalArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Argumento adicional dependendo do tipo de função |

### Valor de retorno

Novo elemento matemático do tipo [IMathFunction](../../imathfunction/)

## Observações

Exemplo: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto logarithmBase = System::MakeObject<MathematicalText>(u"5");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfTwoArguments::Log, logarithmBase);
// Retorna o logaritmo de 'x' na base '5'
```

## MathElementBase::AsArgumentOfFunction(MathFunctionsOfTwoArguments, System::String) método

Utiliza a função especificada usando esta instância como argumento e o argumento adicional especificado

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, System::String additionalArgument) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| functionType | [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/) | Um dos tipos de função comuns de dois argumentos: Log, Lim, Min, Max |
| additionalArgument | [System::String](../../../system/string/) | Argumento adicional dependendo do tipo de função |

### Valor de retorno

Novo elemento matemático do tipo [IMathFunction](../../imathfunction/)

## Observações

Exemplo: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfTwoArguments::Log, u"5");
// Retorna o logaritmo de 'x' na base '5'
```

## Veja também

* Enum [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument/)
* Enum [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* classe [IMathFunction](../../imathfunction/)
* classe [IMathElement](../../imathelement/)
* classe [MathElementBase](../)
* classe [String](../../../system/string/)
* namespace [Aspose::Slides::MathText](../../)
* biblioteca [Aspose.Slides](../../../)