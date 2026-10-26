---
title: Cast()
second_title: Aspose.Slides برای مرجع API C++
description: اشاره‌گر را به نوع خود تبدیل می‌کند.
type: docs
weight: 287
url: /fa/system/smartptr/cast/
---
## SmartPtr::Cast() const متد

اشاره‌گر را به نوع خود تبدیل می‌کند.

```cpp
template<class Y,typename Check> std::enable_if_t<std::is_same<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| Y | نوع هدف شیء اشاره‌شده. |
| Check | پرچم‌ها برای پرتاب استثناء اگر تبدیل موجود نباشد. |

### مقدار بازگشتی

اشاره‌گری از نوع تغییر یافته که همیشه در حالت به‌اشتراک‌گذاری است.

## SmartPtr::Cast() const متد

اشاره‌گر را با استفاده از static_cast به نوع پایه تبدیل می‌کند.

```cpp
template<class Y,typename Check> std::enable_if_t<!std::is_same<Y, T>::value &&std::is_base_of<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| Y | نوع هدف شیء اشاره‌شده. |
| Check | پرچم‌ها برای پرتاب استثناء اگر تبدیل موجود نباشد. |

### مقدار بازگشتی

اشاره‌گری از نوع تغییر یافته که همیشه در حالت به‌اشتراک‌گذاری است.

## SmartPtr::Cast() const متد

اشاره‌گر را با استفاده از dynamic_cast به نوع مشتق تبدیل می‌کند.

```cpp
template<class Y,typename Check> std::enable_if_t<Check::value &&!std::is_same<Y, T>::value &&!std::is_base_of<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| Y | نوع هدف شیء اشاره‌شده. |
| Check | پرچم‌ها برای پرتاب استثناء اگر تبدیل موجود نباشد. |

### مقدار بازگشتی

اشاره‌گری از نوع تغییر یافته که همیشه در حالت به‌اشتراک‌گذاری است. در صورتی که تبدیل موجود نباشد، InvalidCastException را پرتاب می‌کند.

## SmartPtr::Cast() const متد

اشاره‌گر را با استفاده از dynamic_cast به نوع مشتق تبدیل می‌کند.

```cpp
template<class Y,typename Check> std::enable_if_t<!Check::value &&!std::is_same<Y, T>::value &&!std::is_base_of<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| Y | نوع هدف شیء اشاره‌شده. |
| Check | پرچم‌ها برای پرتاب استثناء اگر تبدیل موجود نباشد. |

### مقدار بازگشتی

اشاره‌گری از نوع تغییر یافته که همیشه در حالت به‌اشتراک‌گذاری است. در صورتی که تبدیل موجود نباشد، nullptr را برمی‌گرداند.

## مراجع

* کلاس [SmartPtr](../)
* فضای نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)