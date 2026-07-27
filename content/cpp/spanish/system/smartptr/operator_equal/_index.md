---
title: operator=()
second_title: Referencia de API de Aspose.Slides para C++
description: Asigna por movimiento el objeto SmartPtr. x se vuelve inutilizable.
type: docs
weight: 27
url: /es/system/smartptr/operator_equal/
---
## SmartPtr::operator=(SmartPtr_&&) método

Asigna por movimiento el objeto [SmartPtr](../). x se vuelve inutilizable.

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(SmartPtr_ &&x) noexcept
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | [SmartPtr_](../smartptr_/)&& | Puntero a asignar por movimiento. |

### Valor devuelto

Referencia a este objeto.

## SmartPtr::operator=(const SmartPtr_&) método

Asigna por copia el objeto [SmartPtr](../).

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(const SmartPtr_ &x)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | const [SmartPtr_](../smartptr_/)& | Puntero a asignar por copia. |

### Valor devuelto

Referencia a este objeto.

## SmartPtr::operator=(const SmartPtr<Q>&) método

Asigna por copia el objeto [SmartPtr](../). Realiza las conversiones de tipo requeridas.

```cpp
template<typename Q> SmartPtr_ & System::SmartPtr<T>::operator=(const SmartPtr<Q> &x)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| Q | Tipo del objeto apuntado por x. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | const [SmartPtr](../)<Q>& | Puntero a asignar por copia. |

### Valor devuelto

Referencia a este objeto.

## SmartPtr::operator=(Pointee_ *) método

Asigna un puntero crudo al objeto [SmartPtr](../).

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(Pointee_ *p)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| p | [Pointee_](../pointee_/) * | Valor del puntero a asignar. |

### Valor devuelto

Referencia a este objeto.

## SmartPtr::operator=(std::nullptr_t) método

Establece el valor del puntero a nullptr.

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(std::nullptr_t)
```

### Valor devuelto

Referencia a este objeto.

## Ver también

* Typedef [SmartPtr_](../smartptr_/)
* Typedef [Pointee_](../pointee_/)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)