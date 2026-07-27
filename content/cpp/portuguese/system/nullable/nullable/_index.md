---
title: Nullable()
second_title: Referência da API Aspose.Slides for C++
description: Constrói uma instância que representa um valor nulo.
type: docs
weight: 1
url: /pt/system/nullable/nullable/
---
## Nullable::Nullable() construtor


Constrói uma instância que representa um valor nulo.

```cpp
System::Nullable<T>::Nullable()
```

## Nullable::Nullable(std::nullptr_t) construtor


Constrói uma instância que representa nulo.

```cpp
System::Nullable<T>::Nullable(std::nullptr_t)
```

## Nullable::Nullable(const T1\&) construtor


Constrói uma instância da classe [Nullable](../) que representa o valor especificado convertido (se necessário) ao valor do tipo subjacente T.

```cpp
template<typename T1> System::Nullable<T>::Nullable(const T1 &value)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T1 | O tipo do valor especificado |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const T1\& | Uma referência constante ao valor a ser representado pelo novo objeto [Nullable](../) construído |

## Nullable::Nullable(const Nullable\<T1\>\&) construtor


Constrói uma instância que representa um valor que é representado pelo objeto [Nullable](../) especificado. O objeto nullable especificado pode representar um valor de tipo diferente do tipo subjacente da instância construída, caso em que o valor representado é convertido para um valor do tipo T.

```cpp
template<typename T1> System::Nullable<T>::Nullable(const Nullable<T1> &value)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T1 | O tipo do valor representado pelo objeto [Nullable](../) especificado |

## Veja Também

* Classe [Nullable](../)
* Namespace [System](../../)
* Biblioteca [Aspose.Slides](../../../)