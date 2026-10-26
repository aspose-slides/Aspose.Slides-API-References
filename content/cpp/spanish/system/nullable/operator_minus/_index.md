---
title: operator-()
second_title: Referencia de API de Aspose.Slides para C++
description: Resta valores anulables y valores nulos apuntados.
type: docs
weight: 222
url: /es/system/nullable/operator_minus/
---
## Nullable::operator-(T1) const método

Resta valores anulables y valores nulos apuntados.

```cpp
template<typename T1,typename> Nullable<T> System::Nullable<T>::operator-(T1) const
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T1 | Tipo del operando derecho, debe ser nullptr_t. |

### Valor de retorno

Objeto vacío [Nullable](../).

## Nullable::operator-(const T1&) const método

Resta valores anulables y valores no anulables.

```cpp
template<typename T1,typename> auto System::Nullable<T>::operator-(const T1 &other) const -> Nullable<decltype(get_Value() - other)>
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T1 | Tipo del operando derecho. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| other | const T1\& | valor a restar. |

### Valor de retorno

Resultado de la resta.

## Nullable::operator-(const Nullable\<T1\>\&) const método

Resta valores anulables.

```cpp
template<typename T1> auto System::Nullable<T>::operator-(const Nullable<T1> &other) const -> System::Nullable<decltype(get_Value() - other.get_Value())>
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T1 | Tipo del operando derecho. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | valor a restar. |

### Valor de retorno

Resultado de la resta.

## Véase también

* Clase [Nullable](../)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)