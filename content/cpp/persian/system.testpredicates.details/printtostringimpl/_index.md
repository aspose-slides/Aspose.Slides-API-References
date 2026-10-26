---
title: PrintToStringImpl()
second_title: Aspose.Slides برای مرجع API C++
description: "زیرکلاس System::Object را با استفاده از متد ToString() به رشته تبدیل می‌کند."
type: docs
weight: 14
url: /fa/system.testpredicates.details/printtostringimpl/
---
## System::TestPredicates::Details::PrintToStringImpl(const SharedPtr\<T\>\&, long long) function

[System::Object](../../system/object/) زیرکلاس را با استفاده از متد ToString() به رشته تبدیل می‌کند.

```cpp
template<typename T> std::enable_if<System::Details::HasToString<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const SharedPtr<T> &value, long long s)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع نهایی کلاس. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const [SharedPtr](../../system/sharedptr/)\<T\>\& | اشاره‌گر به شیء برای چاپ. |
| s | long long | یک پارامتر سرویس که به عنوان انتخابگر بارگذاری تابع بر پایه نوع این پارامتر عمل می‌کند؛ مقدار این پارامتر نادیده گرفته می‌شود. |

### مقدار بازگشت

نمایش [String](../../system/string/) از شیء ارسا‌ل‌شده یا "nullptr"، اگر **value** مقدار null داشته باشد.

## System::TestPredicates::Details::PrintToStringImpl(const WeakPtr\<T\>\&, long long) function

[System::Object](../../system/object/) زیرکلاس را با استفاده از متد ToString() به رشته تبدیل می‌کند.

```cpp
template<typename T> std::enable_if<System::Details::HasToString<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const WeakPtr<T> &value, long long s)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع نهایی کلاس. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const [WeakPtr](../../system/weakptr/)\<T\>\& | اشاره‌گر به شیء برای چاپ. |
| s | long long | یک پارامتر سرویس که به عنوان انتخابگر بارگذاری تابع بر پایه نوع این پارامتر عمل می‌کند؛ مقدار این پارامتر نادیده گرفته می‌شود. |

### مقدار بازگشت

نمایش [String](../../system/string/) از شیء ارسا‌ل‌شده یا "nullptr"، اگر **value** مقدار null داشته باشد.

## System::TestPredicates::Details::PrintToStringImpl(const T\&, long long) function

شیء را با استفاده از متد ToString() به رشته تبدیل می‌کند.

```cpp
template<typename T> std::enable_if<!TypeTraits::has_print_to_method<T>::value &&System::Details::HasToString<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const T &value, long long s)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع [Object](../../system/object/). |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) برای چاپ. |
| s | long long | یک پارامتر سرویس که به عنوان انتخابگر بارگذاری تابع بر پایه نوع این پارامتر عمل می‌کند؛ مقدار این پارامتر نادیده گرفته می‌شود. |

### مقدار بازگشت

نمایش [String](../../system/string/) از شیء ارسا‌ل‌شده.

## System::TestPredicates::Details::PrintToStringImpl(const T\&, long long) function

شیء را با استفاده از متد PrintTo به رشته تبدیل می‌کند.

```cpp
template<typename T> std::enable_if<TypeTraits::has_print_to_method<T>::value &&!TypeTraits::IsEnumerable<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const T &value, long long s)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع [Object](../../system/object/). |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) برای چاپ. |
| s | long long | یک پارامتر سرویس که به عنوان انتخابگر بارگذاری تابع بر پایه نوع این پارامتر عمل می‌کند؛ مقدار این پارامتر نادیده گرفته می‌شود. |

### مقدار بازگشت

نمایش [String](../../system/string/) از شیء ارسا‌ل‌شده.

## System::TestPredicates::Details::PrintToStringImpl(const T\&, long long) function

شیء را با استفاده از متد PrintTo به رشته تبدیل می‌کند.

```cpp
template<typename T> std::enable_if<TypeTraits::has_print_to_method<T>::value &&TypeTraits::IsEnumerable<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const T &value, long long s)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع [Object](../../system/object/). |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) برای چاپ. |
| s | long long | یک پارامتر سرویس که به عنوان انتخابگر بارگذاری تابع بر پایه نوع این پارامتر عمل می‌کند؛ مقدار این پارامتر نادیده گرفته می‌شود. |

### مقدار بازگشت

نمایش [String](../../system/string/) از شیء ارسا‌ل‌شده.

## System::TestPredicates::Details::PrintToStringImpl(const std::pair\<T1, T2\>\&, long long) function

جفت را به رشته تبدیل می‌کند.

```cpp
template<typename T1,typename T2> std::string System::TestPredicates::Details::PrintToStringImpl(const std::pair<T1, T2> &value, long long s)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T1 | آرگومان نوع جفت اول. |
| T2 | آرگومان نوع جفت دوم. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const std::pair\<T1, T2\>\& | [Object](../../system/object/) برای چاپ. |
| s | long long | یک پارامتر سرویس که به عنوان انتخابگر بارگذاری تابع بر پایه نوع این پارامتر عمل می‌کند؛ مقدار این پارامتر نادیده گرفته می‌شود. |

### مقدار بازگشت

نمایش رشته‌ای مشترک از هر دو مؤلفه جفت اول و دوم.

## System::TestPredicates::Details::PrintToStringImpl(const Collections::Generic::KeyValuePair\<T1, T2\>\&, long long) function

جفت را به رشته تبدیل می‌کند.

```cpp
template<typename T1,typename T2> std::string System::TestPredicates::Details::PrintToStringImpl(const Collections::Generic::KeyValuePair<T1, T2> &value, long long s)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T1 | آرگومان نوع جفت اول. |
| T2 | آرگومان نوع جفت دوم. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const [Collections::Generic::KeyValuePair](../../system.collections.generic/keyvaluepair/)\<T1, T2\>\& | [Object](../../system/object/) برای چاپ. |
| s | long long | یک پارامتر سرویس که به عنوان انتخابگر بارگذاری تابع بر پایه نوع این پارامتر عمل می‌کند؛ مقدار این پارامتر نادیده گرفته می‌شود. |

### مقدار بازگشت

نمایش رشته‌ای مشترک از هر دو مؤلفه جفت اول و دوم.

## System::TestPredicates::Details::PrintToStringImpl(const T\&, long long) function

محفظه‌های سبک STL را با چاپ عناصرشان (بیش از 32 عنصر نیست) به رشته تبدیل می‌کند.

```cpp
template<typename T> std::enable_if<TypeTraits::IsCppContainer<T>::value &&!std::is_base_of<Object, T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const T &container, long long s)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع [Object](../../system/object/). |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| container | const T\& | [Object](../../system/object/) برای چاپ. |
| s | long long | یک پارامتر سرویس که به عنوان انتخابگر بارگذاری تابع بر پایه نوع این پارامتر عمل می‌کند؛ مقدار این پارامتر نادیده گرفته می‌شود. |

### مقدار بازگشت

نمایش رشته‌ای مشترک از عناصر موجود.

## System::TestPredicates::Details::PrintToStringImpl(const T\&, int) function

سایر انواع را با استفاده از توابع ارائه‌شده توسط gtest به رشته تبدیل می‌کند.

```cpp
template<typename T> std::string System::TestPredicates::Details::PrintToStringImpl(const T &value, int s)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع [Object](../../system/object/). |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) برای چاپ. |
| s | int | یک پارامتر سرویس که به عنوان انتخابگر بارگذاری تابع بر پایه نوع این پارامتر عمل می‌کند؛ مقدار این پارامتر نادیده گرفته می‌شود. |

### مقدار بازگشت

نمایش [String](../../system/string/) از شیء ارسا‌ل‌شده.

## See Also

* تعریف نوع [SharedPtr](../../system/sharedptr/)
* کلاس [WeakPtr](../../system/weakptr/)
* کلاس [KeyValuePair](../../system.collections.generic/keyvaluepair/)
* کلاس [Object](../../system/object/)
* ساختار [has_print_to_method](../../system.testpredicates.typetraits/has_print_to_method/)
* ساختار [IsEnumerable](../../system.testpredicates.typetraits/isenumerable/)
* ساختار [IsCppContainer](../../system.testpredicates.typetraits/iscppcontainer/)
* فضای‌نام [System::TestPredicates::Details](../)
* کتابخانه [Aspose.Slides](../../)