---
title: WeakPtr()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea un puntero nulo.
type: docs
weight: 1
url: /es/system/weakptr/weakptr/
---
## WeakPtr::WeakPtr(std::nullptr_t) constructor

Crea un puntero nulo.

```cpp
System::WeakPtr<T>::WeakPtr(std::nullptr_t=nullptr)
```

## WeakPtr::WeakPtr(Pointee_ *) constructor

Crea un puntero débil al objeto dado.

```cpp
System::WeakPtr<T>::WeakPtr(Pointee_ *object)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| object | [Pointee_](../../smartptr/pointee_/) * | [Object](../../object/) para crear un puntero débil a. |

## WeakPtr::WeakPtr(const SmartPtr_&) constructor

Crea un puntero débil que referencia el mismo puntero al que apunta ptr.

```cpp
System::WeakPtr<T>::WeakPtr(const SmartPtr_ &ptr)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ptr | const [SmartPtr_](../../smartptr/smartptr_/)\& | Puntero del cual copiar el valor apuntado. |

## WeakPtr::WeakPtr(const SmartPtr\<Q\>\&) constructor

Crea un puntero débil que referencia el mismo puntero al que apunta x.

```cpp
template<class Q,typename> System::WeakPtr<T>::WeakPtr(const SmartPtr<Q> &x)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| Q | Tipo del objeto apuntado del puntero origen. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | const [SmartPtr](../../smartptr/)\<Q\>\& | Puntero del cual copiar el valor apuntado. |

## WeakPtr::WeakPtr(const WeakPtr_&) constructor

Copia y construye un puntero débil.

```cpp
System::WeakPtr<T>::WeakPtr(const WeakPtr_ &ptr)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ptr | const [WeakPtr_](../weakptr_/)\& | Puntero del cual copiar el valor apuntado. |

## WeakPtr::WeakPtr(const WeakPtr\<Q\>\&) constructor

Copia y construye un puntero débil.

```cpp
template<class Q,typename> System::WeakPtr<T>::WeakPtr(const WeakPtr<Q> &x)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| Q | Tipo del objeto apuntado de origen. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | const [WeakPtr](../)\<Q\>\& | Puntero del cual copiar el valor apuntado. |

## WeakPtr::WeakPtr(SmartPtr_&&) constructor

Mueve y construye un puntero débil.

```cpp
System::WeakPtr<T>::WeakPtr(SmartPtr_ &&x)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | [SmartPtr_](../../smartptr/smartptr_/)\&& | Puntero del cual mover el valor apuntado. |

## Ver también

* Typedef [Pointee_](../../smartptr/pointee_/)
* Typedef [SmartPtr_](../../smartptr/smartptr_/)
* Typedef [WeakPtr_](../weakptr_/)
* Class [WeakPtr](../)
* Class [SmartPtr](../../smartptr/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)