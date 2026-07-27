---
title: operator<()
second_title: Referência da API Aspose.Slides para C++
description: Sempre retorna false.
type: docs
weight: 170
url: /pt/system/nullable/operator_less/
---
## Nullable::operator<(std::nullptr_t) const método


Sempre retorna false.

```cpp
bool System::Nullable<T>::operator<(std::nullptr_t) const
```

## Nullable::operator<(const T1\&) const método


Determina se o valor representado pelo objeto atual é menor que o valor especificado aplicando [operator<()](./) a esses valores.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator<(const T1 &other) const
```


### Parâmetros de Modelo

| Parâmetro | Descrição |
| --- | --- |
| T1 | O tipo do valor a ser comparado |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| other | const T1\& | Uma referência constante ao valor a ser comparado |

### Valor de Retorno

True se o valor representado pelo objeto atual for menor que o valor especificado, caso contrário - false

## Nullable::operator<(const Nullable\<T1\>\&) const método


Determina se o valor representado pelo objeto atual é menor que o valor representado pelo objeto [Nullable](../) especificado aplicando [operator<()](./) a esses valores.

```cpp
template<typename T1> bool System::Nullable<T>::operator<(const Nullable<T1> &other) const
```


### Parâmetros de Modelo

| Parâmetro | Descrição |
| --- | --- |
| T1 | O tipo subjacente do objeto [Nullable](../) a ser comparado |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | Uma referência constante ao objeto [Nullable](../) a ser comparado |

### Valor de Retorno

True se o valor representado pelo objeto atual for menor que o valor representado pelo objeto [Nullable](../) especificado, caso contrário - false

## Veja Também

* Classe [Nullable](../)
* Estrutura [IsNullable](../../isnullable/)
* Espaço de nomes [System](../../)
* Biblioteca [Aspose.Slides](../../../)