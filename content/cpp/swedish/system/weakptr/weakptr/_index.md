---
title: WeakPtr()
second_title: Aspose.Slides för C++ API-referens
description: Skapar nullpekare.
type: docs
weight: 1
url: /sv/system/weakptr/weakptr/
---
## WeakPtr::WeakPtr(std::nullptr_t) constructor

Skapar nullpekare.

```cpp
System::WeakPtr<T>::WeakPtr(std::nullptr_t=nullptr)
```

## WeakPtr::WeakPtr(Pointee_ *) constructor

Skapar svag pekare till givet objekt.

```cpp
System::WeakPtr<T>::WeakPtr(Pointee_ *object)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| object | [Pointee_](../../smartptr/pointee_/) * | [Object](../../object/) för att skapa svag pekare till. |

## WeakPtr::WeakPtr(const SmartPtr_\&) constructor

Skapar svag pekare som refererar till samma pekare som ptr pekar på.

```cpp
System::WeakPtr<T>::WeakPtr(const SmartPtr_ &ptr)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ptr | const [SmartPtr_](../../smartptr/smartptr_/)\& | Pekare att kopiera pekartvärde från. |

## WeakPtr::WeakPtr(const SmartPtr\<Q\>\&) constructor

Skapar svag pekare som refererar till samma pekare som x pekar på.

```cpp
template<class Q,typename> System::WeakPtr<T>::WeakPtr(const SmartPtr<Q> &x)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Q | Pekartyp för källpekaren. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | const [SmartPtr](../../smartptr/)\<Q\>\& | Pekare att kopiera pekartvärde från. |

## WeakPtr::WeakPtr(const WeakPtr_\&) constructor

Kopierar svag pekare.

```cpp
System::WeakPtr<T>::WeakPtr(const WeakPtr_ &ptr)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ptr | const [WeakPtr_](../weakptr_/)\& | Pekare att kopiera pekartvärde från. |

## WeakPtr::WeakPtr(const WeakPtr\<Q\>\&) constructor

Kopierar svag pekare.

```cpp
template<class Q,typename> System::WeakPtr<T>::WeakPtr(const WeakPtr<Q> &x)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Q | Källpekartyp. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | const [WeakPtr](../)\<Q\>\& | Pekare att kopiera pekartvärde från. |

## WeakPtr::WeakPtr(SmartPtr_\&&) constructor

Flyttar svag pekare.

```cpp
System::WeakPtr<T>::WeakPtr(SmartPtr_ &&x)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | [SmartPtr_](../../smartptr/smartptr_/)\&& | Pekare att flytta pekartvärde från. |

## Se också

* Typedef [Pointee_](../../smartptr/pointee_/)
* Typedef [SmartPtr_](../../smartptr/smartptr_/)
* Typedef [WeakPtr_](../weakptr_/)
* Klass [WeakPtr](../)
* Klass [SmartPtr](../../smartptr/)
* Namnrymd [System](../../)
* Library [Aspose.Slides](../../../)