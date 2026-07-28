---
title: DynamicWeakPtr()
second_title: Aspose.Slides C++ API-referencia
description: Létrehoz egy null okos mutatót.
type: docs
weight: 1
url: /hu/system/dynamicweakptr/dynamicweakptr/
---
## DynamicWeakPtr::DynamicWeakPtr(std::nullptr_t) konstruktor


Létrehoz egy null okos mutatót.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(std::nullptr_t=nullptr)
```

## DynamicWeakPtr::DynamicWeakPtr(Pointee_ *) konstruktor


Létrehoz egy okos mutatót, amely a megadott objektumra mutat.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(Pointee_ *object)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| object | [Pointee_](../../smartptr/pointee_/) * | Célobjektum. |

## DynamicWeakPtr::DynamicWeakPtr(const SmartPtr_\&) konstruktor


Másoló konstruktor egy okos mutatóhoz.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(const SmartPtr_ &ptr)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| ptr | const [SmartPtr_](../smartptr_/)\& | Okos mutató, amelyből a célobjektum információit másolni kell. |

## DynamicWeakPtr::DynamicWeakPtr(const SmartPtr\<Q\>\&) konstruktor


Másoló konstruktor egy okos mutatóhoz.

```cpp
template<class Q> System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(const SmartPtr<Q> &x)
```


### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| Q | Forrás mutató célobjektum típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | const [SmartPtr](../../smartptr/)\<Q\>\& | Okos mutató, amelyből a célobjektum információit másolni kell. |

## DynamicWeakPtr::DynamicWeakPtr(const DynamicWeakPtr_\&) konstruktor


Másoló konstruktor egy okos mutatóhoz.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(const DynamicWeakPtr_ &ptr)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| ptr | const [DynamicWeakPtr_](../dynamicweakptr_/)\& | Okos mutató, amelyből a célobjektum információit másolni kell. |

## DynamicWeakPtr::DynamicWeakPtr(SmartPtr_\&&) konstruktor


Mozgató konstruktor egy okos mutatóhoz.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(SmartPtr_ &&x)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | [SmartPtr_](../smartptr_/)\&& | Okos mutató, amelyből a célobjektum információit mozgatni kell. A hívás után használhatatlan lesz. |

## Lásd még

* Typedef [Pointee_](../../smartptr/pointee_/)
* Typedef [SmartPtr_](../smartptr_/)
* Typedef [DynamicWeakPtr_](../dynamicweakptr_/)
* Class [DynamicWeakPtr](../)
* Class [SmartPtr](../../smartptr/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)