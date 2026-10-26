---
title: GetHashCode()
second_title: مرجع API Aspose.Slides برای C++
description: یک کد هش برای مقدار اسکالر مشخص‌شده بازمی‌گرداند.
type: docs
weight: 2484
url: /fa/system/gethashcode/
---
## System::GetHashCode(const T\&) تابع

یک کد هش برای مقدار اسکالر مشخص‌شده بازگردانده می‌شود.

```cpp
template<typename T> std::enable_if<std::is_scalar<T>::value, int>::type System::GetHashCode(const T &obj)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع مقداری که تابع برای آن کد هش تولید می‌کند |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | const T\& | مقداری که برای آن کد هش تولید می‌شود |

### مقدار بازگشت

کد هش تولید‌شده برای مقدار مشخص‌شده

## System::GetHashCode(const T\&) تابع

یک کد هش برای شیء مشخص‌شده بازگردانده می‌شود.

```cpp
template<typename T> std::enable_if<!std::is_scalar<T>::value &&System::IsSmartPtr<T>::value, int>::type System::GetHashCode(const T &obj)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع شیئی که تابع برای آن کد هش تولید می‌کند |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | const T\& | [SmartPtr](../smartptr/) که به شیء اشاره می‌کند برای تولید کد هش |

### مقدار بازگشت

کد هش تولید‌شده برای شیء مشخص‌شده

## System::GetHashCode(const T\&) تابع

یک کد هش برای شیء مشخص‌شده که یک استثنا است بازگردانده می‌شود.

```cpp
template<typename T> std::enable_if<System::IsExceptionWrapper<T>::value, int>::type System::GetHashCode(const T &obj)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع شیئی که تابع برای آن کد هش تولید می‌کند |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | const T\& | Exception Wrapper که شامل شیء‌ای است که برای آن کد هش تولید می‌شود |

### مقدار بازگشت

کد هش تولید‌شده برای شیء مشخص‌شده

## System::GetHashCode(const T\&) تابع

یک کد هش برای شیء مشخص‌شده که اشاره‌گر هوشمند یا استثنا نیست بازگردانده می‌شود.

```cpp
template<typename T> std::enable_if<!std::is_scalar<T>::value &&!System::IsSmartPtr<T>::value &&!System::IsExceptionWrapper<T>::value, int>::type System::GetHashCode(const T &obj)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع شیئی که تابع برای آن کد هش تولید می‌کند |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | const T\& | یک ارجاع const به شیء‌ای که برای آن کد هش تولید می‌شود |

### مقدار بازگشت

کد هش تولید‌شده برای شیء مشخص‌شده

## System::GetHashCode(const std::thread::id\&) تابع

تخصیص ویژه برای std::thread::id؛ کد هش برای شیء نخ مشخص‌شده بازگردانده می‌شود.

```cpp
int System::GetHashCode(const std::thread::id &id)
```

## موارد مرتبط

* ساختار [IsSmartPtr](../issmartptr/)
* ساختار [IsExceptionWrapper](../isexceptionwrapper/)
* فضای نام [System](../)
* کتابخانه [Aspose.Slides](../../)