---
title: AsArgumentOfFunction()
second_title: Referência da API Aspose.Slides para C++
description: Utiliza a função especificada usando esta instância como argumento
type: docs
weight: 66
url: /pt/aspose.slides.mathtext/imathelement/asargumentoffunction/
---
## IMathElement::AsArgumentOfFunction(System::SharedPtr\<IMathElement\>) método


Utiliza a função especificada usando esta instância como argumento

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(System::SharedPtr<IMathElement> functionName)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| functionName | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Nome da função |

### Valor de Retorno

Novo elemento matemático do tipo [IMathFunction](../../imathfunction/)
## Observações



Exemplo: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(functionName);
```

## IMathElement::AsArgumentOfFunction(System::String) método


Utiliza a função especificada usando esta instância como argumento

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(System::String functionName)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| functionName | [System::String](../../../system/string/) | Nome da função |

### Valor de Retorno

Novo elemento matemático do tipo [IMathFunction](../../imathfunction/)
## Observações



Exemplo: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(u"cos");
```

## IMathElement::AsArgumentOfFunction(MathFunctionsOfOneArgument) método


Utiliza a função especificada usando esta instância como argumento

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(MathFunctionsOfOneArgument functionType)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| functionType | [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument/) | Um dos tipos de função comuns de um argumento |

### Valor de Retorno

Novo elemento matemático do tipo [IMathFunction](../../imathfunction/)
## Observações



Exemplo: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfOneArgument::ArcSin);
```

## IMathElement::AsArgumentOfFunction(MathFunctionsOfTwoArguments, System::SharedPtr\<IMathElement\>) método


Utiliza a função especificada usando esta instância como argumento e o argumento adicional especificado

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, System::SharedPtr<IMathElement> additionalArgument)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| functionType | [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/) | Um dos tipos de função comuns de dois argumentos: Log, Lim, Min, Max |
| additionalArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Argumento adicional dependendo do tipo de função |

### Valor de Retorno

Novo elemento matemático do tipo [IMathFunction](../../imathfunction/)
## Observações



Exemplo: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto logarithmBase = System::MakeObject<MathematicalText>(u"5");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfTwoArguments::Log, logarithmBase);
// Retorna o logaritmo de 'x' na base '5'
```

## IMathElement::AsArgumentOfFunction(MathFunctionsOfTwoArguments, System::String) método


Utiliza a função especificada usando esta instância como argumento e o argumento adicional especificado

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, System::String additionalArgument)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| functionType | [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/) | Um dos tipos de função comuns de dois argumentos: Log, Lim, Min, Max |
| additionalArgument | [System::String](../../../system/string/) | Argumento adicional dependendo do tipo de função |

### Valor de Retorno

Novo elemento matemático do tipo [IMathFunction](../../imathfunction/)
## Observações



Exemplo: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfTwoArguments::Log, u"5");
// Retorna o logaritmo de 'x' na base '5'
```

## Veja Também

* Enum [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument/)
* Enum [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* classe [IMathFunction](../../imathfunction/)
* classe [IMathElement](../)
* classe [String](../../../system/string/)
* namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)