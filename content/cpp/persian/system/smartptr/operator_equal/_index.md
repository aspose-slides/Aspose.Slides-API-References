---
title: operator=()
second_title: مرجع API Aspose.Slides برای C++
description: به صورت انتقالی به شیء SmartPtr مقداردهی می‌کند. x غیرقابل استفاده می‌شود.
type: docs
weight: 27
url: /fa/system/smartptr/operator_equal/
---
## SmartPtr::operator=(SmartPtr_&&) متد

به صورت انتقالی به شیء [SmartPtr](../) مقداردهی می‌کند. x غیرقابل استفاده می‌شود.

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(SmartPtr_ &&x) noexcept
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | [SmartPtr_](../smartptr_/)&& | اشاره‌گر برای انتقال مقداردهی. |

### مقدار بازگشت

مرجع به این شیء.

## SmartPtr::operator=(const SmartPtr_&) متد

به صورت کپی به شیء [SmartPtr](../) مقداردهی می‌کند.

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(const SmartPtr_ &x)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | const [SmartPtr_](../smartptr_/)& | اشاره‌گر برای کپی مقداردهی. |

### مقدار بازگشت

مرجع به این شیء.

## SmartPtr::operator=(const SmartPtr\<Q\>&) متد

به صورت کپی به شیء [SmartPtr](../) مقداردهی می‌کند. تبدیل‌های نوع مورد نیاز را انجام می‌دهد.

```cpp
template<typename Q> SmartPtr_ & System::SmartPtr<T>::operator=(const SmartPtr<Q> &x)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| Q | نوع شیء ای که x به آن اشاره می‌کند. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | const [SmartPtr](../)\<Q\>& | اشاره‌گر برای کپی مقداردهی. |

### مقدار بازگشت

مرجع به این شیء.

## SmartPtr::operator=(Pointee_ *) متد

مقداردهی اشاره‌گر خام به شیء [SmartPtr](../) انجام می‌دهد.

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(Pointee_ *p)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| p | [Pointee_](../pointee_/) * | مقدار اشاره‌گر برای مقداردهی. |

### مقدار بازگشت

مرجع به این شیء.

## SmartPtr::operator=(std::nullptr_t) متد

مقدار اشاره‌گر را به nullptr تنظیم می‌کند.

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(std::nullptr_t)
```

### مقدار بازگشت

مرجع به این شیء.

## موارد مرتبط

* تعریف نوع [SmartPtr_](../smartptr_/)
* تعریف نوع [Pointee_](../pointee_/)
* کلاس [SmartPtr](../)
* فضای نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)