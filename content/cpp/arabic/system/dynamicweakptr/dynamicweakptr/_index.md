---
title: DynamicWeakPtr()
second_title: مرجع API Aspose.Slides لـ C++
description: ينشئ مؤشرًا ذكيًا فارغًا.
type: docs
weight: 1
url: /ar/system/dynamicweakptr/dynamicweakptr/
---
## DynamicWeakPtr::DynamicWeakPtr(std::nullptr_t) منشئ

Creates null smart pointer.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(std::nullptr_t=nullptr)
```

## DynamicWeakPtr::DynamicWeakPtr(Pointee_ *) منشئ

Creates smart pointer pointing to given object.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(Pointee_ *object)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| object | [Pointee_](../../smartptr/pointee_/) * | الكائن المشار إليه. |

## DynamicWeakPtr::DynamicWeakPtr(const SmartPtr_\&) منشئ

Copy-constructs smart pointer.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(const SmartPtr_ &ptr)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| ptr | const [SmartPtr_](../smartptr_/)\& | المؤشر الذكي لنسخ معلومات الكائن المشار إليه منه. |

## DynamicWeakPtr::DynamicWeakPtr(const SmartPtr\<Q\>\&) منشئ

Copy-constructs smart pointer.

```cpp
template<class Q> System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(const SmartPtr<Q> &x)
```

### Template parameters

| Parameter | Description |
| --- | --- |
| Q | نوع الكائن المشير إليه في المصدر. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | const [SmartPtr](../../smartptr/)\<Q\>\& | المؤشر الذكي لنسخ معلومات الكائن المشير إليه منه. |

## DynamicWeakPtr::DynamicWeakPtr(const DynamicWeakPtr_\&) منشئ

Copy-constructs smart pointer.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(const DynamicWeakPtr_ &ptr)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| ptr | const [DynamicWeakPtr_](../dynamicweakptr_/)\& | المؤشر الذكي لنسخ معلومات الكائن المشير إليه منه. |

## DynamicWeakPtr::DynamicWeakPtr(SmartPtr_\&&) منشئ

Move-constructs smart pointer.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(SmartPtr_ &&x)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | [SmartPtr_](../smartptr_/)\&& | المؤشر الذكي لنقل معلومات الكائن المشير إليه منه. يصبح غير قابل للاستخدام بعد الاستدعاء. |

## See Also

* Typedef [Pointee_](../../smartptr/pointee_/)
* Typedef [SmartPtr_](../smartptr_/)
* Typedef [DynamicWeakPtr_](../dynamicweakptr_/)
* Class [DynamicWeakPtr](../)
* Class [SmartPtr](../../smartptr/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)