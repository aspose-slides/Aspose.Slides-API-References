---
title: DynamicWeakPtr()
second_title: Aspose.Slides för C++ API-referens
description: Skapar null smartpekare.
type: docs
weight: 1
url: /sv/system/dynamicweakptr/dynamicweakptr/
---
## DynamicWeakPtr::DynamicWeakPtr(std::nullptr_t) konstruktor


Skapar null smartpekare.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(stdnullptr_t=nullptr)
```

## DynamicWeakPtr::DynamicWeakPtr(Pointee_ *) konstruktor


Skapar smartpekare som pekar på angivet objekt.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(Pointee_ *object)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| object | [Pointee_](../../smartptr/pointee_/) * | Pekarobjekt. |

## DynamicWeakPtr::DynamicWeakPtr(const SmartPtr_\&) konstruktor


Kopierar smartpekare.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(const SmartPtr_ &ptr)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ptr | const [SmartPtr_](../smartptr_/)\& | Smartpekare att kopiera pekarobjektinformation från. |

## DynamicWeakPtr::DynamicWeakPtr(const SmartPtr\<Q\>\&) konstruktor


Kopierar smartpekare.

```cpp
template<class Q> System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(const SmartPtr<Q> &x)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Q | Källpekare pekarobjekttyp. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | const [SmartPtr](../../smartptr/)\<Q\>\& | Smartpekare att kopiera pekarobjektinformation från. |

## DynamicWeakPtr::DynamicWeakPtr(const DynamicWeakPtr_\&) konstruktor


Kopierar smartpekare.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(const DynamicWeakPtr_ &ptr)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ptr | const [DynamicWeakPtr_](../dynamicweakptr_/)\& | Smartpekare att kopiera pekarobjektinformation från. |

## DynamicWeakPtr::DynamicWeakPtr(SmartPtr_\&&) konstruktor


Flyttar smartpekare.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(SmartPtr_ &&x)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | [SmartPtr_](../smartptr_/)\&& | Smartpekare att flytta pekarobjektinformation från. Blir oanvändbar efter anropet. |

## Se även

* Typedef [Pointee_](../../smartptr/pointee_/)
* Typedef [SmartPtr_](../smartptr_/)
* Typedef [DynamicWeakPtr_](../dynamicweakptr_/)
* Klass [DynamicWeakPtr](../)
* Klass [SmartPtr](../../smartptr/)
* Namnområde [System](../../)
* Bibliotek [Aspose.Slides](../../../)