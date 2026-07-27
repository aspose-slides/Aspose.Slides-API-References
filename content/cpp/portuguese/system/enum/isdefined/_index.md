---
title: IsDefined()
second_title: Aspose.Slides para C++ Referência da API
description: Determina se o valor especificado é um membro do tipo de enumeração E.
type: docs
weight: 27
url: /pt/system/enum/isdefined/
---
## Enum::IsDefined(E) método


Determina se o valor especificado é um membro do tipo de enumeração **E**.

```cpp
static bool System::Enum<E, Guard>::IsDefined(E value)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | E | O valor a ser verificado |

### Valor de Retorno

Verdadeiro se **value** for um membro da enumeração **E**, caso contrário - falso

## Enum::IsDefined(T) método


Determina se o valor especificado é um membro do tipo de enumeração **T**.

```cpp
template<class T> static std::enable_if<std::is_convertible<T, UnderlyingType>::value, bool>::type System::Enum<E, Guard>::IsDefined(T value)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | T | O valor a ser verificado |

### Valor de Retorno

Verdadeiro se **value** for um membro da enumeração **T**, caso contrário - falso

## Enum::IsDefined(const String\&) método


Determina se o valor com o nome especificado está entre os membros da enum **E**.

```cpp
static bool System::Enum<E, Guard>::IsDefined(const String &name)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | const [String](../../string/)\& | O nome a ser verificado |

### Valor de Retorno

Verdadeiro se existir um membro da enum **E** com o nome especificado.

## Veja Também

* Typedef [UnderlyingType](../underlyingtype/)
* Classe [String](../../string/)
* Estrutura [Enum](../)
* Espaço de nomes [System](../../)
* Biblioteca [Aspose.Slides](../../../)