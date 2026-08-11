---
title: ReferenceEquals()
second_title: Aspose.Slides برای C++ مرجع API
description: "تخصیص خاص Object::ReferenceEquals برای مورد رشته و nullptr."
type: docs
weight: 261
url: /fa/system/object/referenceequals/
---
## Object::ReferenceEquals(String const\&, std::nullptr_t) متد

تخصیص خاص [Object::ReferenceEquals](./) برای مورد رشته و nullptr.

```cpp
bool System::Object::ReferenceEquals(String const &str, std::nullptr_t)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| str | [String](../../string/) const\& | [String](../../string/) برای مقایسه با nullptr. |

### مقدار بازگشت

true اگر رشته null باشد، در غیر این صورت false.

## Object::ReferenceEquals(String const\&, String const\&) متد

تخصیص خاص [Object::ReferenceEquals](./) برای مورد رشته‌ها.

```cpp
bool System::Object::ReferenceEquals(String const &str1, String const &str2)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| str1 | [String](../../string/) const\& | اولین رشته برای مقایسه. |
| str2 | [String](../../string/) const\& | دومین رشته برای مقایسه. |

### مقدار بازگشت

true اگر رشته‌ها برابر باشند، در غیر این صورت false.

## Object::ReferenceEquals(ptr const\&, ptr const\&) متد

اشیاء را بر اساس ارجاع مقایسه می‌کند.

```cpp
static bool System::Object::ReferenceEquals(ptr const &objA, ptr const &objB)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| objA | [ptr](../ptr/) const\& | اولین اشاره‌گر برای مقایسه. |
| objB | [ptr](../ptr/) const\& | دومین اشاره‌گر برای مقایسه. |

### مقدار بازگشت

True اگر اشاره‌گرها برابر باشند و در غیر این صورت false.

## Object::ReferenceEquals(T const\&, T const\&) متد

اشیاء را بر اساس ارجاع مقایسه می‌کند.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, bool>::type System::Object::ReferenceEquals(T const &objA, T const &objB)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع اشیائی که مقایسه می‌شوند. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| objA | T const\& | اولین شیء برای مقایسه. |
| objB | T const\& | دومین شیء برای مقایسه. |

### مقدار بازگشت

True اگر آدرس‌های اشیاء برابر باشند و در غیر این صورت false.

## Object::ReferenceEquals(T const\&, std::nullptr_t) متد

مقایسه ارجاعی شیء نوع مقدار با nullptr.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, bool>::type System::Object::ReferenceEquals(T const &objA, std::nullptr_t)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع شیء برای مقایسه. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| objA | T const\& | اولین شیء برای مقایسه. |

### مقدار بازگشت

همیشه false برمی‌گرداند زیرا انواع مقدار نمی‌توانند null شوند.

## موارد مرتبط

* Typedef [ptr](../ptr/)
* کلاس [String](../../string/)
* کلاس [Object](../)
* Struct [IsSmartPtr](../../issmartptr/)
* فضای‌نام [System](../../)
* Library [Aspose.Slides](../../../)