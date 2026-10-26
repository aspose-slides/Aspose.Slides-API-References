---
title: Get()
second_title: مرجع API Aspose.Slides برای C++
description: عملکردی برای دریافت عنصر N-ام از تاپل داده‌شده. بارگذاری برای شی پایه.
type: docs
weight: 2406
url: /fa/system/get/
---
## System::Get(const SharedPtr\<Object\>\&) تابع

عملکردی برای دریافت عنصر N-ام از تاپل داده‌شده. بارگذاری برای شی پایه.

```cpp
template<std::size_t> auto System::Get(const SharedPtr<Object> &object)
```


### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| N | شاخص عنصر. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| object | const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\& | شی برای بررسی. |

### مقدار بازگشت

مقدار عنصر N-ام تاپل تبدیل‌شده به شی.

## System::Get(const T\&) تابع

عملکردی برای دریافت عنصر N-ام از تاپل داده‌شده. بارگذاری برای شیئهایی که متد Deconstruct دارند.

```cpp
template<std::size_t,typename T> auto System::Get(const T &object)
```


### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| N | شاخص عنصر. |
| T | نوع شیء بررسی‌شده. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| object | const T\& | شی برای بررسی. |

### مقدار بازگشت

مقدار عنصر N-ام تاپل.

## System::Get(const SharedPtr\<T\>\&) تابع


عملکردی برای دریافت عنصر N-ام از تاپل داده‌شده. بارگذاری برای اشاره‌گرهای مشترک.

```cpp
template<std::size_t,typename T> auto System::Get(const SharedPtr<T> &pointer)
```


### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| N | شاخص عنصر. |
| T | نوع شیء بررسی‌شده. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| object | const [SharedPtr](../sharedptr/)\<T\>\& | شی برای بررسی. |

### مقدار بازگشت

مقدار عنصر N-ام تاپل.

## System::Get(T\&, const Index\&) تابع

پیاده‌سازی برای عبارات collection[index].

```cpp
template<typename T> auto & System::Get(T &collection, const Index &index)
```


### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع مجموعه. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| collection | T\& | شی مجموعه. |
| index | const [Index](../index/)\& | شاخص عنصر از نوع [System.Index](../index/). |

### مقدار بازگشت

عنصر مجموعه در جابجایی محاسبه‌شده.

## System::Get(T\&, const Range\&) تابع

یک برش از مجموعه مشخص‌شده که توسط بازه‌ی ارائه‌شده تعریف می‌شود را برمی‌گرداند.

```cpp
template<typename T> auto System::Get(T &collection, const Range &range)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| collection | T\& | مجموعه‌ای که برش داده می‌شود. |
| range | const [Range](../range/)\& | بازه‌ای که مرزهای برش را مشخص می‌کند. |

### مقدار بازگشت

یک نمای یا برش از مجموعه از جابجایی شروع محاسبه‌شده و طول.

## System::Get(const ValueTuple\<Args...\>\&) تابع

عنصر N-ام از تاپل مقدار را دریافت می‌کند.

```cpp
template<std::size_t,typename...> auto System::Get(const ValueTuple<Args...> &tuple)
```


### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| N | شاخص عنصر. |
| Args | عناصر تاپل. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| tuple | const [ValueTuple](../valuetuple/)\<Args...\>\& | تاپل برای دریافت عنصر. |

### مقدار بازگشت

مقدار عنصر N-ام تاپل.

## موارد مرتبط

* تعریف نوع [SharedPtr](../sharedptr/)
* کلاس [Object](../object/)
* کلاس [Index](../index/)
* کلاس [Range](../range/)
* کلاس [ValueTuple](../valuetuple/)
* فضای‌نام [System](../)
* کتابخانه [Aspose.Slides](../../)