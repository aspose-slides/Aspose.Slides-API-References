---
title: Function()
second_title: Referência da API Aspose.Slides para C++
description: Aceita uma função de um argumento usando esta instância como nome da função
type: docs
weight: 53
url: /pt/aspose.slides.mathtext/imathelement/function/
---
## IMathElement::Function(System::SharedPtr\<IMathElement\>) método

Aceita uma função de um argumento usando esta instância como nome da função

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::Function(System::SharedPtr<IMathElement> functionArgument)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| functionArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Um argumento da função |

### Valor de Retorno

Novo elemento matemático do tipo [IMathFunction](../../imathfunction/)

## Observações

Exemplo: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionName->Function(functionArg);
```

## IMathElement::Function(System::String) método

Aceita uma função de um argumento usando esta instância como nome da função

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::Function(System::String functionArgument)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| functionArgument | [System::String](../../../system/string/) | Um argumento da função |

### Valor de Retorno

Novo elemento matemático do tipo [IMathFunction](../../imathfunction/)

## Observações

Exemplo: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto func = functionName->Function(u"x");
```

## Ver Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathFunction](../../imathfunction/)
* Classe [IMathElement](../)
* Classe [String](../../../system/string/)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)