---
title: operator+()
second_title: Referencia de API de Aspose.Slides para C++
description: Devuelve una instancia construida por defecto de la clase Nullable<T>.
type: docs
weight: 209
url: /es/system/nullable/operator_plus/
---
## Nullable::operator+(std::nullptr_t) const método

Devuelve una instancia construida por defecto de la clase Nullable<T>.

```cpp
Nullable<T> System::Nullable<T>::operator+(std::nullptr_t) const
```

## Nullable::operator+(const T1\&) const método

Suma valores anulables y no anulables.

```cpp
template<typename T1,typename> auto System::Nullable<T>::operator+(const T1 &other) const -> Nullable<decltype(get_Value()+other)>
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T1 | Tipo del operando derecho. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| other | const T1\& | valor a añadir. |

### Valor de retorno

Resultado de la suma.

## Nullable::operator+(const Nullable\<T1\>\&) const método

Suma valores anulables.

```cpp
template<typename T1> auto System::Nullable<T>::operator+(const Nullable<T1> &other) const -> System::Nullable<decltype(get_Value()+other.get_Value())>
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T1 | Tipo del operando derecho. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | valor a añadir. |

### Valor de retorno

Resultado de la suma.

## Véase también

* Clase [Nullable](../)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)