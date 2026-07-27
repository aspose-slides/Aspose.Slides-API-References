---
title: operator=()
second_title: Referencia de API de Aspose.Slides para C++
description: Asigna por movimiento el puntero inteligente.
type: docs
weight: 27
url: /es/system/dynamicweakptr/operator_equal/
---
## DynamicWeakPtr::operator=(SmartPtr_&&) método

Asigna por movimiento el puntero inteligente.

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(SmartPtr_ &&x)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | [SmartPtr_](../smartptr_/)&& | Puntero del cual se asigna por movimiento el valor. |

### Valor de retorno

Referencia a sí mismo.

## DynamicWeakPtr::operator=(const SmartPtr_&) método

Asigna por copia el puntero inteligente.

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(const SmartPtr_ &x)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | const [SmartPtr_](../smartptr_/)& | Puntero del cual se copia el valor para asignar. |

### Valor de retorno

Referencia a sí mismo.

## DynamicWeakPtr::operator=(const SmartPtr<Q>&) método

Asigna por copia el puntero inteligente.

```cpp
template<typename Q> DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(const SmartPtr<Q> &x)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| Q | Tipo del objeto apuntado de origen. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | const [SmartPtr](../../smartptr/)<Q>& | Puntero del cual se copia el valor para asignar. |

### Valor de retorno

Referencia a sí mismo.

## DynamicWeakPtr::operator=(typename SmartPtr_::Pointee_ *) método

Asigna el puntero inteligente.

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(typename SmartPtr_::Pointee_ *p)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| p | typename [SmartPtr_::Pointee_](../../smartptr/pointee_/) * | Valor del puntero. |

### Valor de retorno

Referencia a sí mismo.

## DynamicWeakPtr::operator=(std::nullptr_t) método

Establece el puntero inteligente a nulo.

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(std::nullptr_t)
```

### Valor de retorno

Referencia a sí mismo.

## Ver también

* Typedef [DynamicWeakPtr_](../dynamicweakptr_/)
* Typedef [SmartPtr_](../smartptr_/)
* Typedef [Pointee_](../../smartptr/pointee_/)
* Class [DynamicWeakPtr](../)
* Class [SmartPtr](../../smartptr/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)