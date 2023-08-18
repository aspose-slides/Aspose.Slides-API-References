---
title: DynamicWeakPtr()
second_title: Aspose.Slides for C++ API Reference
description: Creates null smart pointer.
type: docs
weight: 1
url: /system/dynamicweakptr/dynamicweakptr/
---
## DynamicWeakPtr::DynamicWeakPtr(std::nullptr_t) constructor


Creates null smart pointer.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(std::nullptr_t=nullptr)
```

## DynamicWeakPtr::DynamicWeakPtr(Pointee_ *) constructor


Creates smart pointer pointing to given object.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(Pointee_ *object)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| object | [Pointee_](../../smartptr/pointee_/) * | Pointee. |

## DynamicWeakPtr::DynamicWeakPtr(const SmartPtr_\&) constructor


Copy-constructs smart pointer.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(const SmartPtr_ &ptr)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| ptr | const [SmartPtr_](../smartptr_/)\& | Smart pointer to copy pointee information from. |

## DynamicWeakPtr::DynamicWeakPtr(const SmartPtr\<Q\>\&) constructor


Copy-constructs smart pointer.

```cpp
template<class Q> System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(const SmartPtr<Q> &x)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| Q | Source pointer pointee type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | const [SmartPtr](../../smartptr/)\<Q\>\& | Smart pointer to copy pointee information from. |

## DynamicWeakPtr::DynamicWeakPtr(const DynamicWeakPtr_\&) constructor


Copy-constructs smart pointer.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(const DynamicWeakPtr_ &ptr)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| ptr | const [DynamicWeakPtr_](../dynamicweakptr_/)\& | Smart pointer to copy pointee information from. |

## DynamicWeakPtr::DynamicWeakPtr(SmartPtr_\&&) constructor


Move-constructs smart pointer.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(SmartPtr_ &&x)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | [SmartPtr_](../smartptr_/)\&& | Smart pointer to move pointee information from. Becomes unusable after call. |

## See Also

* Typedef [Pointee_](../../smartptr/pointee_/)
* Typedef [SmartPtr_](../smartptr_/)
* Typedef [DynamicWeakPtr_](../dynamicweakptr_/)
* Class [DynamicWeakPtr](../)
* Class [SmartPtr](../../smartptr/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)