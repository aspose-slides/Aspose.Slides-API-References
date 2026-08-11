---
title: operator=()
second_title: مرجع API Aspose.Slides برای C++
description: به‌صورت حرکتی به اشاره‌گر هوشمند انتساب می‌دهد.
type: docs
weight: 27
url: /fa/system/dynamicweakptr/operator_equal/
---
## DynamicWeakPtr::operator=(SmartPtr_&&) متد

به‌صورت حرکتی به اشاره‌گر هوشمند انتساب می‌دهد.

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(SmartPtr_ &&x)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | [SmartPtr_](../smartptr_/)\&& | Pointer to move-assign value from. |

### مقدار بازگشت

مرجع خود.

## DynamicWeakPtr::operator=(const SmartPtr_&) متد

به‌صورت کپی به اشاره‌گر هوشمند انتساب می‌دهد.

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(const SmartPtr_ &x)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | const [SmartPtr_](../smartptr_/)\& | Pointer to copy-assign value from. |

### مقدار بازگشت

مرجع خود.

## DynamicWeakPtr::operator=(const SmartPtr\<Q\>\&) متد

به‌صورت کپی به اشاره‌گر هوشمند انتساب می‌دهد.

```cpp
template<typename Q> DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(const SmartPtr<Q> &x)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| Q | Source pointee type. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | const [SmartPtr](../../smartptr/)\<Q\>\& | Pointer to copy-assign value from. |

### مقدار بازگشت

مرجع خود.

## DynamicWeakPtr::operator=(typename SmartPtr_::Pointee_ *) متد

به اشاره‌گر هوشمند انتساب می‌دهد.

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(typename SmartPtr_::Pointee_ *p)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| p | typename [SmartPtr_::Pointee_](../../smartptr/pointee_/) * | Pointer value. |

### مقدار بازگشت

مرجع خود.

## DynamicWeakPtr::operator=(std::nullptr_t) متد

مقدار اشاره‌گر هوشمند را به null تنظیم می‌کند.

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(std::nullptr_t)
```

### مقدار بازگشت

مرجع خود.

## موارد مرتبط

* Typedef [DynamicWeakPtr_](../dynamicweakptr_/)
* Typedef [SmartPtr_](../smartptr_/)
* Typedef [Pointee_](../../smartptr/pointee_/)
* کلاس [DynamicWeakPtr](../)
* کلاس [SmartPtr](../../smartptr/)
* فضای‌نام [System](../../)
* Library [Aspose.Slides](../../../)