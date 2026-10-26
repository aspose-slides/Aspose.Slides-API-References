---
title: operator!=()
second_title: Referência da API Aspose.Slides para C++
description: Determina se o valor representado pelo objeto atual não é nulo.
type: docs
weight: 144
url: /pt/system/nullable/operator_not_equal/
---
## Nullable::operator!=(std::nullptr_t) const method

Determina se o valor representado pelo objeto atual não é nulo.

```cpp
bool System::Nullable<T>::operator!=(std::nullptr_t) const
```

### Valor de retorno

True se o valor representado pelo objeto atual não for nulo, caso contrário - false

## Nullable::operator!=(const T1\&) const method

Determina se o valor representado pelo objeto atual não é igual ao valor especificado.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator!=(const T1 &other) const
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T1 | O tipo do valor para comparar com |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| other | const T1\& | Uma referência constante ao valor para comparar com |

### Valor de retorno

True se o valor representado pelo objeto atual não for igual ao valor especificado, caso contrário - false

## Nullable::operator!=(const Nullable\<T1\>\&) const method

Determina se o valor representado pelo objeto atual não é igual ao valor representado pelo objeto [Nullable](../) especificado.

```cpp
template<typename T1> bool System::Nullable<T>::operator!=(const Nullable<T1> &other) const
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T1 | O tipo subjacente do objeto [Nullable](../) para comparar com |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | Uma referência constante ao objeto [Nullable](../) para comparar com |

### Valor de retorno

True se o valor representado pelo objeto atual não for igual ao valor representado pelo objeto [Nullable](../) especificado, caso contrário - false

## Ver também

* Classe [Nullable](../)
* Estrutura [IsNullable](../../isnullable/)
* Espaço de nomes [System](../../)
* Biblioteca [Aspose.Slides](../../../)