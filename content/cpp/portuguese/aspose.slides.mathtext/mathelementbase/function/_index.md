---
title: Function()
second_title: Aspose.Slides para C++ Referência da API
description: Recebe uma função de um argumento usando esta instância como o nome da função
type: docs
weight: 40
url: /pt/aspose.slides.mathtext/mathelementbase/function/
---
## MathElementBase::Function(System::SharedPtr\<IMathElement\>) método


Recebe uma função de um argumento usando esta instância como o nome da função

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::Function(System::SharedPtr<IMathElement> functionArgument) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| functionArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Um argumento da função |

### Valor de Retorno

Novo elemento matemático do tipo [IMathFunction](../../imathfunction/)
## Observações



Exemplo: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionName->Function(functionArg);
```

## MathElementBase::Function(System::String) método


Recebe uma função de um argumento usando esta instância como o nome da função

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::Function(System::String functionArgument) override
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

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathFunction](../../imathfunction/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathElementBase](../)
* Classe [String](../../../system/string/)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)