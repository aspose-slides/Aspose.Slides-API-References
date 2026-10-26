---
title: DynamicWeakPtr()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een null smart pointer aan.
type: docs
weight: 1
url: /nl/system/dynamicweakptr/dynamicweakptr/
---
## DynamicWeakPtr::DynamicWeakPtr(std::nullptr_t) constructor

Maakt een null smart pointer aan.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(std::nullptr_t=nullptr)
```

## DynamicWeakPtr::DynamicWeakPtr(Pointee_ *) constructor

Maakt een smart pointer die naar het opgegeven object wijst.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(Pointee_ *object)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| object | [Pointee_](../../smartptr/pointee_/) * | Pointee. |

## DynamicWeakPtr::DynamicWeakPtr(const SmartPtr_\&) constructor

Constructeert een smart pointer via kopiëren.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(const SmartPtr_ &ptr)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| ptr | const [SmartPtr_](../smartptr_/)\& | Smart pointer waarvan de pointee-informatie wordt gekopieerd. |

## DynamicWeakPtr::DynamicWeakPtr(const SmartPtr\<Q\>\&) constructor

Constructeert een smart pointer via kopiëren.

```cpp
template<class Q> System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(const SmartPtr<Q> &x)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| Q | Bron pointer pointee type. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | const [SmartPtr](../../smartptr/)\<Q\>\& | Smart pointer waarvan de pointee-informatie wordt gekopieerd. |

## DynamicWeakPtr::DynamicWeakPtr(const DynamicWeakPtr_\&) constructor

Constructeert een smart pointer via kopiëren.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(const DynamicWeakPtr_ &ptr)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| ptr | const [DynamicWeakPtr_](../dynamicweakptr_/)\& | Smart pointer waarvan de pointee-informatie wordt gekopieerd. |

## DynamicWeakPtr::DynamicWeakPtr(SmartPtr_\&&) constructor

Constructeert een smart pointer via verplaatsing.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(SmartPtr_ &&x)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | [SmartPtr_](../smartptr_/)\&& | Smart pointer waarvan de pointee-informatie wordt verplaatst. Wordt onbruikbaar na aanroep. |

## Zie ook

* Typedef [Pointee_](../../smartptr/pointee_/)
* Typedef [SmartPtr_](../smartptr_/)
* Typedef [DynamicWeakPtr_](../dynamicweakptr_/)
* Class [DynamicWeakPtr](../)
* Class [SmartPtr](../../smartptr/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)