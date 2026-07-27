---
title: operator>()
second_title: Referência da API Aspose.Slides para C++
description: Sempre retorna false.
type: docs
weight: 157
url: /pt/system/nullable/operator_greater/
---
## Nullable::operator>(std::nullptr_t) const método


Sempre retorna false.

```cpp
bool System::Nullable<T>::operator>(std::nullptr_t) const
```

## Nullable::operator>(const T1\&) const método


Determina se o valor representado pelo objeto atual é maior que o valor especificado ao aplicar [operator>()](./) a esses valores.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator>(const T1 &other) const
```


### Parâmetros de modelo

| Parameter | Description |
| --- | --- |
| T1 | The type of the value to compare with |

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| other | const T1\& | A constant reference to the value to compare with |

### Valor de retorno

True se o valor representado pelo objeto atual for maior que o valor especificado, caso contrário - false

## Nullable::operator>(const Nullable\<T1\>\&) const método


Determina se o valor representado pelo objeto atual é maior que o valor representado pelo objeto [Nullable](../) especificado ao aplicar [operator>()](./) a esses valores.

```cpp
template<typename T1> bool System::Nullable<T>::operator>(const Nullable<T1> &other) const
```


### Parâmetros de modelo

| Parameter | Description |
| --- | --- |
| T1 | The underlying type of the [Nullable](../) object to compare with |

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | A constant reference to the [Nullable](../) object to compare with |

### Valor de retorno

True se o valor representado pelo objeto atual for maior que o valor representado pelo objeto [Nullable](../) especificado, caso contrário - false

## Ver também

* Classe [Nullable](../)
* Estrutura [IsNullable](../../isnullable/)
* Namespace [System](../../)
* Biblioteca [Aspose.Slides](../../../)