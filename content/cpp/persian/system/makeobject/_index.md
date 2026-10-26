---
title: MakeObject()
second_title: Aspose.Slides برای C++ مرجع API
description: شی را روی heap ایجاد می‌کند و اشاره‌گر مشترک به آن را برمی‌گرداند.
type: docs
weight: 2887
url: /fa/system/makeobject/
---
## System::MakeObject(Args\&&...) تابع


شی را روی heap ایجاد می‌کند و اشاره‌گر مشترک به آن را برمی‌گرداند.

```cpp
template<class T,class ...> std::enable_if<!IsSmartPtr<T>::value, SmartPtr<T>>::type System::MakeObject(Args &&... args)
```


### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | کلاس برای نمونه‌سازی. |
| Args | نوع آرگومان‌های سازنده. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| args | Args\&&... | آرگومان‌های سازنده. |

### مقدار بازگشتی

[SmartPtr](../smartptr/) به شیء تازه ایجاد شده، همیشه در حالت shared.

## System::MakeObject(Args\&&...) تابع


شی را روی heap ایجاد می‌کند و اشاره‌گر مشترک به آن را برمی‌گرداند.

```cpp
template<class T,class ...> std::enable_if<IsSmartPtr<T>::value, T>::type System::MakeObject(Args &&... args)
```


### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | [SmartPtr](../smartptr/) به کلاس برای نمونه‌سازی. |
| Args | نوع آرگومان‌های سازنده. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| args | Args\&&... | آرگومان‌های سازنده. |

### مقدار بازگشتی

[SmartPtr](../smartptr/) به شیء تازه ایجاد شده، همیشه در حالت shared.

## موارد مرتبط

* کلاس [SmartPtr](../smartptr/)
* ساختار [IsSmartPtr](../issmartptr/)
* فضای‌نام [System](../)
* کتابخانه [Aspose.Slides](../../)