---
title: operator-()
second_title: Referência da API Aspose.Slides para C++
description: Subtrai valores nullable e valores com ponteiro nulo.
type: docs
weight: 222
url: /pt/system/nullable/operator_minus/
---
## Nullable::operator-(T1) const método


Subtrai valores nullable e valores com ponteiro nulo.

```cpp
template<typename T1,typename> Nullable<T> System::Nullable<T>::operator-(T1) const
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T1 | Tipo do operando direito, deve ser nullptr_t. |

### Valor de retorno

Objeto [Nullable](../) vazio.

## Nullable::operator-(const T1\&) const método


Subtrai valores nullable e valores não nullable.

```cpp
template<typename T1,typename> auto System::Nullable<T>::operator-(const T1 &other) const -> Nullable<decltype(get_Value() - other)>
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T1 | Tipo do operando direito. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| other | const T1\& | valor a subtrair. |

### Valor de retorno

Resultado da subtração.

## Nullable::operator-(const Nullable\<T1\>\&) const método


Subtrai valores nullable.

```cpp
template<typename T1> auto System::Nullable<T>::operator-(const Nullable<T1> &other) const -> System::Nullable<decltype(get_Value() - other.get_Value())>
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T1 | Tipo do operando direito. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | valor a subtrair. |

### Valor de retorno

Resultado da subtração.

## Veja Também

* Classe [Nullable](../)
* Namespace [System](../../)
* Biblioteca [Aspose.Slides](../../../)