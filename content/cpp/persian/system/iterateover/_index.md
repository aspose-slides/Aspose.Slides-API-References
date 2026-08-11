---
title: IterateOver()
second_title: مرجع API Aspose.Slides برای C++
description: "این ویژگی تابع شی enumerable (یا iterable) را می‌پیچاند تا بتوان از آن در حلقه for مبتنی بر بازه استفاده کرد. این بارگذاری برای Enumerable بدون متدهای begin()، end() با آرگومان نوع هدف برای (auto& value : IterateOver<SomeType>(enumerable))"
type: docs
weight: 2471
url: /fa/system/iterateover/
---
## System::IterateOver(System::SmartPtr\<Enumerable\>) تابع

این ویژگی تابع، شی enumerable (یا iterable) را می‌پیچاند تا بتوان از آن در حلقه for مبتنی بر بازه استفاده کرد. این بارگذاری برای Enumerable بدون متدهای begin()، end() با آرگومان نوع هدف برای (auto& value : IterateOver<SomeType>(enumerable))

```cpp
template<typename T,typename Enumerable> std::enable_if_t<!Details::IsIterable<Enumerable>::value, Details::EnumeratorAdapter<Enumerable, T>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع هدف، باید از iterator بازگردانده شود |
| Enumerable | نوع شیء بسته‌شده |

## System::IterateOver(System::SmartPtr\<Enumerable\>) تابع

این ویژگی تابع، شی enumerable (یا iterable) را می‌پیچاند تا بتوان از آن در حلقه for مبتنی بر بازه استفاده کرد. این بارگذاری برای Enumerable بدون متدهای begin()، end() با نوع هدف پیش‌فرض برای (auto& value : IterateOver(enumerable)) مشابه کد C# زیر foreach (var value in enumerable)

```cpp
template<typename Enumerable> std::enable_if_t<!Details::IsIterable<Enumerable>::value, Details::EnumeratorAdapter<Enumerable>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| Enumerable | نوع شیء بسته‌شده |

## System::IterateOver(System::SmartPtr\<Enumerable\>) تابع

این ویژگی تابع، شی enumerable (یا iterable) را می‌پیچاند تا بتوان از آن در حلقه for مبتنی بر بازه استفاده کرد. این بارگذاری برای Enumerable با متدهای begin()، end() با نوع هدف پیش‌فرض برای (auto& value : IterateOver(enumerable))

```cpp
template<typename Enumerable> std::enable_if_t<Details::IsIterable<Enumerable>::value, System::SmartPtr<Enumerable>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| Enumerable | نوع شیء بسته‌شده |

## System::IterateOver(System::SmartPtr\<Enumerable\>) تابع

این ویژگی تابع، شی enumerable (یا iterable) را می‌پیچاند تا بتوان از آن در حلقه for مبتنی بر بازه استفاده کرد. این بارگذاری برای Enumerable با متدهای begin()، end() با نوع هدف همانند value_type اصلی iterator.

```cpp
template<typename T,typename Enumerable> std::enable_if_t<Details::IsIterable<Enumerable>::value &&std::is_same<typename Details::ReturnTypeTrait<T>::ReturnType, Details::IterableValueType<Enumerable>>::value, System::SmartPtr<Enumerable>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| Enumerable | نوع شیء بسته‌شده |
| T | نوع هدف که باید از iterator بازگردانده شود |

## System::IterateOver(System::SmartPtr\<Enumerable\>) تابع

این ویژگی تابع، شی enumerable (یا iterable) را می‌پیچاند تا بتوان از آن در حلقه for مبتنی بر بازه استفاده کرد. این بارگذاری برای Enumerable با متدهای begin()، end() با نوع هدف متفاوت و value_type اصلی iterator.

```cpp
template<typename T,typename Enumerable> std::enable_if_t<Details::IsIterable<Enumerable>::value &&!std::is_same<typename Details::ReturnTypeTrait<T>::ReturnType, Details::IterableValueType<Enumerable>>::value, Details::CppIteratorAdapter<Enumerable, T>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| Enumerable | نوع شیء بسته‌شده |
| T | نوع هدف که باید از iterator بازگردانده شود |

## System::IterateOver(const Enumerable *) تابع

این ویژگی تابع، شی enumerable (یا iterable) را می‌پیچاند تا بتوان از آن در حلقه for مبتنی بر بازه استفاده کرد. این بارگذاری برای Enumerable این با نوع هدف پیش‌فرض.

```cpp
template<typename Enumerable> std::enable_if_t<!IsSmartPtr<Enumerable>::value, Details::EnumeratorAdapter<Enumerable, Details::ValueTypeOfEnumerable<Enumerable>, Enumerable *>> System::IterateOver(const Enumerable *enumerable)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| Enumerable | نوع شیء بسته‌شده |

## System::IterateOver(const Enumerable *) تابع

این ویژگی تابع، شی enumerable (یا iterable) را می‌پیچاند تا بتوان از آن در حلقه for مبتنی بر بازه استفاده کرد. این بارگذاری برای Enumerable بدون متدهای begin()، end() با آرگومان نوع هدف برای (auto& value : IterateOver<SomeType>(enumerable))

```cpp
template<typename T,typename Enumerable> std::enable_if_t<!IsSmartPtr<Enumerable>::value, Details::EnumeratorAdapter<Enumerable, T, Enumerable *>> System::IterateOver(const Enumerable *enumerable)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع هدف، باید از iterator بازگردانده شود |
| Enumerable | نوع شیء بسته‌شده |

## همچنین ببینید

* کلاس [SmartPtr](../smartptr/)
* ساختار [IsSmartPtr](../issmartptr/)
* فضای نام [System](../)
* کتابخانه [Aspose.Slides](../../)