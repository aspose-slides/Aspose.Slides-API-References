---
title: operator>=()
second_title: Referência da API Aspose.Slides para C++
description: Sempre retorna false.
type: docs
weight: 183
url: /pt/system/nullable/operator_greater_equal/
---
## Nullable::operator>=(std::nullptr_t) const method

Sempre retorna false.

```cpp
bool System::Nullable<T>::operator>=(std::nullptr_t) const
```

### Valor de retorno

Sempre - false

## Nullable::operator>=(const T1\&) const method

Determina se o valor representado pelo objeto atual é maior ou igual ao valor representado pelo objeto especificado aplicando [operator>=()](./) a esses valores.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator>=(const T1 &other) const
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T1 | O tipo subjacente do valor para comparar com o valor representado pelo objeto atual |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| other | const T1\& | Uma referência constante a um objeto para comparar com o objeto atual |

### Valor de retorno

True se o valor representado pelo objeto atual for maior ou igual ao valor representado pelo objeto especificado, caso contrário - false

## Nullable::operator>=(const Nullable\<T1\>\&) const method

Determina se o valor representado pelo objeto atual é maior ou igual ao valor representado pelo objeto [Nullable](../) especificado aplicando [operator>=()](./) a esses valores.

```cpp
template<typename T1> bool System::Nullable<T>::operator>=(const Nullable<T1> &other) const
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T1 | O tipo subjacente do objeto [Nullable](../) para comparar |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | Uma referência constante ao objeto [Nullable](../) para comparar |

### Valor de retorno

True se o valor representado pelo objeto atual for maior ou igual ao valor representado pelo objeto [Nullable](../) especificado, caso contrário - false

## Veja Também

* Classe [Nullable](../)
* Estrutura [IsNullable](../../isnullable/)
* Namespace [System](../../)
* Biblioteca [Aspose.Slides](../../../)