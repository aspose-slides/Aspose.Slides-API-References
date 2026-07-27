---
title: Enum
second_title: Referência da API Aspose.Slides para C++
description: Fornece métodos que executam algumas operações em valores do tipo enum. Este é um tipo estático sem serviços de instância. Você nunca deve criar instâncias dele por nenhum meio.
type: docs
weight: 1587
url: /pt/system/enum/
---
## Estrutura Enum

Fornece métodos que executam algumas operações em valores do tipo enum. Este é um tipo estático sem serviços de instância. Você nunca deve criar instâncias dele por nenhum meio.

```cpp
template<class E,class Guard>class Enum
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| E | O tipo de enum cujos valores são manipulados pela classe |
| Guard | Argumento de tipo de serviço cujo objetivo é garantir que **E** seja um tipo enumerável |

## Métodos

| Método | Descrição |
| --- | --- |
| static int [Compare](./compare/)(E, T) | Realiza a comparação aritmética dos valores das constantes de enumeração especificadas. |
| static std::enable_if\<std::is_same\<T, E\>::value||std::is_convertible\<T, [UnderlyingType](./underlyingtype/)\>::value, [String](../string/)\>::type [GetDescription](./getdescription/)(T) | Retorna o nome da constante de enumeração que possui o valor especificado. |
| static std::enable_if\<std::is_same\<T, E\>::value||std::is_convertible\<T, [UnderlyingType](./underlyingtype/)\>::value, [String](../string/)\>::type [GetName](./getname/)(T) | Retorna o nome da constante de enumeração que possui o valor especificado. |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetNames](./getnames/)() | Retorna uma matriz contendo os nomes de todos os membros da enumeração **E**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetUnderlyingType](./getunderlyingtype/)() | Retorna o tipo subjacente da enumeração. |
| static [ArrayPtr](../arrayptr/)\<E\> [GetValues](./getvalues/)() | Retorna uma matriz contendo todos os membros da enumeração **E**. |
| static **bool** [HasFlag](./hasflag/)(E, E) | Determina se os bits especificados estão definidos em uma representação binária do valor da enumeração especificado. |
| static **bool** [IsDefined](./isdefined/)(E) | Determina se o valor especificado é um membro do tipo de enumeração **E**. |
| static std::enable_if\<std::is_convertible\<T, [UnderlyingType](./underlyingtype/)\>::value, **bool**\>::type [IsDefined](./isdefined/)(T) | Determina se o valor especificado é um membro do tipo de enumeração **T**. |
| static **bool** [IsDefined](./isdefined/)(const [String](../string/)\&) | Determina se o valor com o nome especificado está entre os membros da enum **E**. |
| static E [Parse](./parse/)(const [String](../string/)\&, **bool**) | Converte a string especificada em constante enum equivalente. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, E\&) | Tenta converter a string especificada em constante enum equivalente. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **bool**, E\&) | Tenta converter a string especificada em constante enum equivalente. |

## Definições de tipo

| Typedef | Descrição |
| --- | --- |
| [UnderlyingType](./underlyingtype/) | Alias para o tipo subjacente do enum. |

## Veja também

* Namespace [System](../)
* Library [Aspose.Slides](../../)