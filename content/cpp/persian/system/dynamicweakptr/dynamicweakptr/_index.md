---
title: DynamicWeakPtr()
second_title: مرجع API Aspose.Slides برای C++
description: یک اشاره‌گر هوشمند تهی ایجاد می‌کند.
type: docs
weight: 1
url: /fa/system/dynamicweakptr/dynamicweakptr/
---
## DynamicWeakPtr::DynamicWeakPtr(std::nullptr_t) سازنده

یک اشاره‌گر هوشمند تهی ایجاد می‌کند.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(std::nullptr_t=nullptr)
```

## DynamicWeakPtr::DynamicWeakPtr(Pointee_ *) سازنده

یک اشاره‌گر هوشمند که به شیء داده‌شده اشاره می‌کند ایجاد می‌کند.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(Pointee_ *object)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| object | [Pointee_](../../smartptr/pointee_/) * | شیء مورد اشاره. |

## DynamicWeakPtr::DynamicWeakPtr(const SmartPtr_\&) سازنده

یک اشاره‌گر هوشمند را به‌صورت کپی‌سازنده ایجاد می‌کند.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(const SmartPtr_ &ptr)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| ptr | const [SmartPtr_](../smartptr_/)\& | اشاره‌گر هوشمند برای کپی‌برداری اطلاعات شیء مورد اشاره. |

## DynamicWeakPtr::DynamicWeakPtr(const SmartPtr\<Q\>\&) سازنده

یک اشاره‌گر هوشمند را به‌صورت کپی‌سازنده ایجاد می‌کند.

```cpp
template<class Q> System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(const SmartPtr<Q> &x)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| Q | نوع شیء مورد اشاره‌ی اشاره‌گر منبع. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | const [SmartPtr](../../smartptr/)\<Q\>\& | اشاره‌گر هوشمند برای کپی‌برداری اطلاعات شیء مورد اشاره. |

## DynamicWeakPtr::DynamicWeakPtr(const DynamicWeakPtr_\&) سازنده

یک اشاره‌گر هوشمند را به‌صورت کپی‌سازنده ایجاد می‌کند.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(const DynamicWeakPtr_ &ptr)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| ptr | const [DynamicWeakPtr_](../dynamicweakptr_/)\& | اشاره‌گر هوشمند برای کپی‌برداری اطلاعات شیء مورد اشاره. |

## DynamicWeakPtr::DynamicWeakPtr(SmartPtr_\&&) سازنده

یک اشاره‌گر هوشمند را به‌صورت انتقالی‌سازنده ایجاد می‌کند.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(SmartPtr_ &&x)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | [SmartPtr_](../smartptr_/)\&& | اشاره‌گر هوشمند برای انتقال اطلاعات شیء مورد اشاره. پس از فراخوانی غیرقابل استفاده می‌شود. |

## موارد مرتبط

* Typedef [Pointee_](../../smartptr/pointee_/)
* Typedef [SmartPtr_](../smartptr_/)
* Typedef [DynamicWeakPtr_](../dynamicweakptr_/)
* کلاس [DynamicWeakPtr](../)
* کلاس [SmartPtr](../../smartptr/)
* فضای نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)