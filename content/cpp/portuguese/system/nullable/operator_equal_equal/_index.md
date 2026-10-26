---
title: operator==()
second_title: Aspose.Slides para C++ Referência da API
description: Determina se o valor representado pelo objeto atual é nulo.
type: docs
weight: 118
url: /pt/system/nullable/operator_equal_equal/
---
## Nullable::operator==(std::nullptr_t) const method

Determina se o valor representado pelo objeto atual é nulo.

```cpp
bool System::Nullable<T>::operator==(std::nullptr_t) const
```

### Valor de Retorno

True se o valor representado pelo objeto atual for nulo, caso contrário - false

## Nullable::operator==(const T1\&) const method

Determina se o valor representado pelo objeto atual é igual ao valor especificado.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator==(const T1 &other) const
```

### Parâmetros de Modelo

| Parameter | Description |
| --- | --- |
| T1 | O tipo do valor a ser comparado |

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| other | const T1\& | Uma referência constante ao valor a ser comparado |

### Valor de Retorno

True se o valor representado pelo objeto atual for igual ao valor especificado, caso contrário - false

## Nullable::operator==(const Nullable\<T1\>\&) const method

Determina se o valor representado pelo objeto atual é igual ao valor representado pelo objeto [Nullable](../) especificado.

```cpp
template<typename T1> bool System::Nullable<T>::operator==(const Nullable<T1> &other) const
```

### Parâmetros de Modelo

| Parameter | Description |
| --- | --- |
| T1 | O tipo subjacente do objeto [Nullable](../) a ser comparado |

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | Uma referência constante ao objeto [Nullable](../) a ser comparado |

### Valor de Retorno

True se o valor representado pelo objeto atual for igual ao valor representado pelo objeto [Nullable](../) especificado, caso contrário - false

## Veja Também

* Class [Nullable](../)
* Struct [IsNullable](../../isnullable/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)