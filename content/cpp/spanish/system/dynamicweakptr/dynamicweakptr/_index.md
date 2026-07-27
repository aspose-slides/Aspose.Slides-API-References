---
title: DynamicWeakPtr()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea un puntero inteligente nulo.
type: docs
weight: 1
url: /es/system/dynamicweakptr/dynamicweakptr/
---
## DynamicWeakPtr::DynamicWeakPtr(std::nullptr_t) constructor

Crea un puntero inteligente nulo.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(std::nullptr_t=nullptr)
```

## DynamicWeakPtr::DynamicWeakPtr(Pointee_ *) constructor

Crea un puntero inteligente que apunta al objeto dado.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(Pointee_ *object)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| object | [Pointee_](../../smartptr/pointee_/) * | Objeto apuntado. |

## DynamicWeakPtr::DynamicWeakPtr(const SmartPtr_\&) constructor

Copia un puntero inteligente.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(const SmartPtr_ &ptr)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ptr | const [SmartPtr_](../smartptr_/)\& | Puntero inteligente del cual copiar la información del objeto apuntado. |

## DynamicWeakPtr::DynamicWeakPtr(const SmartPtr\<Q\>\&) constructor

Copia un puntero inteligente.

```cpp
template<class Q> System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(const SmartPtr<Q> &x)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| Q | Tipo del objeto apuntado del puntero fuente. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | const [SmartPtr](../../smartptr/)\<Q\>\& | Puntero inteligente del cual copiar la información del objeto apuntado. |

## DynamicWeakPtr::DynamicWeakPtr(const DynamicWeakPtr_\&) constructor

Copia un puntero inteligente.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(const DynamicWeakPtr_ &ptr)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ptr | const [DynamicWeakPtr_](../dynamicweakptr_/)\& | Puntero inteligente del cual copiar la información del objeto apuntado. |

## DynamicWeakPtr::DynamicWeakPtr(SmartPtr_\&&) constructor

Construye mediante movimiento un puntero inteligente.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(SmartPtr_ &&x)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | [SmartPtr_](../smartptr_/)\&& | Puntero inteligente del cual mover la información del objeto apuntado. Se vuelve inutilizable después de la llamada. |

## Ver también

* Typedef [Pointee_](../../smartptr/pointee_/)
* Typedef [SmartPtr_](../smartptr_/)
* Typedef [DynamicWeakPtr_](../dynamicweakptr_/)
* Class [DynamicWeakPtr](../)
* Class [SmartPtr](../../smartptr/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)