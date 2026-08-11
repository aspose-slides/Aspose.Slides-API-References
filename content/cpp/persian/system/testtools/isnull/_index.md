---
title: IsNull()
second_title: مرجع API Aspose.Slides برای C++
description: بررسی می‌کند که آیا مقدار خاصی null است. نسخه برای انواع عددی و شمارشی.
type: docs
weight: 1
url: /fa/system/testtools/isnull/
---
## TestTools::IsNull(T) متد

بررسی می‌کند که آیا مقدار خاصی null است. [Version](../../version/) برای انواع عددی و شمارشی.

```cpp
template<typename T> static std::enable_if<std::is_arithmetic<T>::value||std::is_enum<T>::value, bool>::type System::TestTools::IsNull(T obj)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع مقدار بررسی‌شده. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | T | مقداری که برای null بررسی می‌شود. |

### مقدار بازگشت

همواره false بر می‌گرداند.

## TestTools::IsNull(const T&) متد

بررسی می‌کند که آیا مقدار خاصی null است. [Version](../../version/) برای انواع غیر عددی و غیر شمارشی.

```cpp
template<typename T> static std::enable_if<!std::is_arithmetic<T>::value &&!std::is_enum<T>::value, bool>::type System::TestTools::IsNull(const T &obj)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع مقدار بررسی‌شده. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | const T\& | مقداری که برای null بررسی می‌شود. |

### مقدار بازگشت

در صورتی که شیء با nullptr مقایسه شود true بر می‌گرداند، در غیر این صورت false.

## TestTools::IsNull(const SharedPtr\<T\>\&) متد

بررسی می‌کند که آیا مقدار خاصی null است. [Version](../../version/) برای انواع غیر عددی.

```cpp
template<typename T> static bool System::TestTools::IsNull(const SharedPtr<T> &obj)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع مقدار بررسی‌شده. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<T\>\& | مقداری که برای null بررسی می‌شود. |

### مقدار بازگشت

در صورتی که شیء با nullptr مقایسه شود true بر می‌گرداند، در غیر این صورت false.

## TestTools::IsNull(System::Collections::Generic::KeyValuePair\<K, V\>\&) متد

بررسی می‌کند که آیا مقدار خاصی null است. [Version](../../version/) برای جفت‌های کلید-مقدار.

```cpp
template<typename K,typename V> static bool System::TestTools::IsNull(System::Collections::Generic::KeyValuePair<K, V> &kvp)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| K | نوع کلید. |
| V | نوع مقدار. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| kvp | [System::Collections::Generic::KeyValuePair](../../../system.collections.generic/keyvaluepair/)\<K, V\>\& | شیء جفت. |

### مقدار بازگشت

در صورتی که جفت به عنوان null در نظر گرفته شود true بر می‌گرداند، در غیر این صورت false.

## TestTools::IsNull(const System::String\&) متد

بررسی می‌کند که آیا رشته null است.

```cpp
static bool System::TestTools::IsNull(const System::String &str)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| str | const [System::String](../../string/)\& | [String](../../string/) برای بررسی. |

### مقدار بازگشت

در صورتی که رشته به عنوان null در نظر گرفته شود true بر می‌گرداند، در غیر این صورت false.

## موارد مرتبط

* تعریف نوع [SharedPtr](../../sharedptr/)
* کلاس [KeyValuePair](../../../system.collections.generic/keyvaluepair/)
* کلاس [String](../../string/)
* ساختار [TestTools](../)
* فضای‌نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)