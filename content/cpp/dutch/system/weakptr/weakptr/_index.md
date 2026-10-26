---
title: WeakPtr()
second_title: Aspose.Slides voor C++ API-referentie
description: Creëert een null-pointer.
type: docs
weight: 1
url: /nl/system/weakptr/weakptr/
---
## WeakPtr::WeakPtr(std::nullptr_t) constructor

Creëert een null-pointer.

```cpp
System::WeakPtr<T>::WeakPtr(std::nullptr_t=nullptr)
```

## WeakPtr::WeakPtr(Pointee_ *) constructor

Creëert een zwakke pointer naar het opgegeven object.

```cpp
System::WeakPtr<T>::WeakPtr(Pointee_ *object)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| object | [Pointee_](../../smartptr/pointee_/) * | [Object](../../object/) om een zwakke pointer te maken naar. |

## WeakPtr::WeakPtr(const SmartPtr_\&) constructor

Creëert een zwakke pointer die naar dezelfde pointer wijst als ptr.

```cpp
System::WeakPtr<T>::WeakPtr(const SmartPtr_ &ptr)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| ptr | const [SmartPtr_](../../smartptr/smartptr_/)\& | Pointer om de pointee-waarde van te kopiëren. |

## WeakPtr::WeakPtr(const SmartPtr\<Q\>\&) constructor

Creëert een zwakke pointer die naar dezelfde pointer wijst als x.

```cpp
template<class Q,typename> System::WeakPtr<T>::WeakPtr(const SmartPtr<Q> &x)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| Q | Pointee-type van de bronpointer. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | const [SmartPtr](../../smartptr/)\<Q\>\& | Pointer om de pointee-waarde van te kopiëren. |

## WeakPtr::WeakPtr(const WeakPtr_\&) constructor

Kopieert een zwakke pointer.

```cpp
System::WeakPtr<T>::WeakPtr(const WeakPtr_ &ptr)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| ptr | const [WeakPtr_](../weakptr_/)\& | Pointer om de pointee-waarde van te kopiëren. |

## WeakPtr::WeakPtr(const WeakPtr\<Q\>\&) constructor

Kopieert een zwakke pointer.

```cpp
template<class Q,typename> System::WeakPtr<T>::WeakPtr(const WeakPtr<Q> &x)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| Q | Bron-pointee-type. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | const [WeakPtr](../)\<Q\>\& | Pointer om de pointee-waarde van te kopiëren. |

## WeakPtr::WeakPtr(SmartPtr_\&&) constructor

Verplaatst een zwakke pointer.

```cpp
System::WeakPtr<T>::WeakPtr(SmartPtr_ &&x)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | [SmartPtr_](../../smartptr/smartptr_/)\&& | Pointer om de pointee-waarde te verplaatsen. |

## Zie ook

* Typedef [Pointee_](../../smartptr/pointee_/)
* Typedef [SmartPtr_](../../smartptr/smartptr_/)
* Typedef [WeakPtr_](../weakptr_/)
* Class [WeakPtr](../)
* Class [SmartPtr](../../smartptr/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)