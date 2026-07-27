---
title: operator<=()
second_title: Referência da API Aspose.Slides para C++
description: Sempre retorna false.
type: docs
weight: 196
url: /pt/system/nullable/operator_less_equal/
---
## Nullable::operator<=(std::nullptr_t) const method


Sempre retorna false.

```cpp
bool System::Nullable<T>::operator<=(std::nullptr_t) const
```

## Nullable::operator<=(const T1\&) const method


Determina se o valor representado pelo objeto atual é menor ou igual ao valor especificado aplicando [operator<=()](./) a esses valores.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator<=(const T1 &other) const
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T1 | O tipo do valor a ser comparado |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| other | const T1\& | Uma referência constante ao valor a ser comparado |

### Valor de retorno

True se o valor representado pelo objeto atual for menor ou igual ao valor especificado, caso contrário - false

## Nullable::operator<=(const Nullable\<T1\>\&) const method


Determina se o valor representado pelo objeto atual é menor ou igual ao valor representado pelo objeto [Nullable](../) especificado aplicando [operator<=()](./) a esses valores.

```cpp
template<typename T1> bool System::Nullable<T>::operator<=(const Nullable<T1> &other) const
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T1 | O tipo subjacente do objeto [Nullable](../) a ser comparado |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | Uma referência constante ao objeto [Nullable](../) a ser comparado |

### Valor de retorno

True se o valor representado pelo objeto atual for menor ou igual ao valor representado pelo objeto [Nullable](../) especificado, caso contrário - false

## See Also

* Classe [Nullable](../)
* Estrutura [IsNullable](../../isnullable/)
* Espaço de nomes [System](../../)
* Biblioteca [Aspose.Slides](../../../)