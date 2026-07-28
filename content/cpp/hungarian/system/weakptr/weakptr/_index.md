---
title: WeakPtr()
second_title: Aspose.Slides C++ API referencia
description: Létrehoz egy null mutatót.
type: docs
weight: 1
url: /hu/system/weakptr/weakptr/
---
## WeakPtr::WeakPtr(std::nullptr_t) konstruktor

Létrehoz egy null mutatót.

```cpp
System::WeakPtr<T>::WeakPtr(std::nullptr_t=nullptr)
```

## WeakPtr::WeakPtr(Pointee_ *) konstruktor

Létrehoz gyenge mutatót a megadott objektumhoz.

```cpp
System::WeakPtr<T>::WeakPtr(Pointee_ *object)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| object | [Pointee_](../../smartptr/pointee_/) * | [Object](../../object/) a gyenge mutató létrehozásához. |

## WeakPtr::WeakPtr(const SmartPtr_\&) konstruktor

Létrehoz gyenge mutatót, amely ugyanarra a mutatóra hivatkozik, amire a ptr mutat.

```cpp
System::WeakPtr<T>::WeakPtr(const SmartPtr_ &ptr)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| ptr | const [SmartPtr_](../../smartptr/smartptr_/)\& | Mutató a pontelő értékének másolásához. |

## WeakPtr::WeakPtr(const SmartPtr\<Q\>\&) konstruktor

Létrehoz gyenge mutatót, amely ugyanarra a mutatóra hivatkozik, amire az x mutat.

```cpp
template<class Q,typename> System::WeakPtr<T>::WeakPtr(const SmartPtr<Q> &x)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| Q | Forrás mutató típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | const [SmartPtr](../../smartptr/)\<Q\>\& | Mutató a pontelő értékének másolásához. |

## WeakPtr::WeakPtr(const WeakPtr_\&) konstruktor

Másolatkonstruktorral hoz létre gyenge mutatót.

```cpp
System::WeakPtr<T>::WeakPtr(const WeakPtr_ &ptr)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| ptr | const [WeakPtr_](../weakptr_/)\& | Mutató a pontelő értékének másolásához. |

## WeakPtr::WeakPtr(const WeakPtr\<Q\>\&) konstruktor

Másolatkonstruktorral hoz létre gyenge mutatót.

```cpp
template<class Q,typename> System::WeakPtr<T>::WeakPtr(const WeakPtr<Q> &x)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| Q | Forrás pontelő típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | const [WeakPtr](../)\<Q\>\& | Mutató a pontelő értékének másolásához. |

## WeakPtr::WeakPtr(SmartPtr_\&&) konstruktor

Mozgatáskonstruktorral hoz létre gyenge mutatót.

```cpp
System::WeakPtr<T>::WeakPtr(SmartPtr_ &&x)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | [SmartPtr_](../../smartptr/smartptr_/)\&& | Mutató a pontelő értékének áthelyezéséhez. |

## Lásd még

* Typedef [Pointee_](../../smartptr/pointee_/)
* Typedef [SmartPtr_](../../smartptr/smartptr_/)
* Typedef [WeakPtr_](../weakptr_/)
* Class [WeakPtr](../)
* Class [SmartPtr](../../smartptr/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)