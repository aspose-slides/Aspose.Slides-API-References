---
title: TestTools
second_title: راهنمای API Aspose.Slides برای C++
description: یک مجموعه از متدهای مفید را فراهم می‌کند که برخی ویژگی‌های پایه انواع مختلف و توابع را بررسی می‌کنند.
type: docs
weight: 1925
url: /fa/system/testtools/
---
## ساختار TestTools

یک مجموعه از متدهای مفید را فراهم می‌کند که برخی ویژگی‌های پایه انواع مختلف و توابع را بررسی می‌کنند.

```cpp
class TestTools
```

## متدها

| متد | توضیح |
| --- | --- |
| static **bool** [AssertThrows](./assertthrows/)(const std::function\<void()>\&) | بررسی می‌کند که تابع استثنایی از هر نوعی پرتاب می‌کند. |
| static **bool** [IsEmpty](./isempty/)(const [System::String](../string/)\&) | بررسی می‌کند که رشته خالی است. |
| static **bool** [IsEmpty](./isempty/)(const [SharedPtr](../sharedptr/)\<T\>\&) | بررسی می‌کند که مجموعه خالی است. |
| static std::enable_if\<std::is_arithmetic\<T\>::value||std::is_enum\<T\>::value, **bool**\>::type [IsNull](./isnull/)(T) | بررسی می‌کند که مقدار خاص تهی است. [Version](../version/) برای انواع عددی و شمارشی. |
| static std::enable_if<\!std::is_arithmetic\<T\>::value\&&\!std::is_enum\<T\>::value, **bool**\>::type [IsNull](./isnull/)(const T\&) | بررسی می‌کند که مقدار خاص تهی است. [Version](../version/) برای انواع غیر عددی و غیر شمارشی. |
| static **bool** [IsNull](./isnull/)(const [SharedPtr](../sharedptr/)\<T\>\&) | بررسی می‌کند که مقدار خاص تهی است. [Version](../version/) برای انواع غیر عددی. |
| static **bool** [IsNull](./isnull/)([System::Collections::Generic::KeyValuePair](../../system.collections.generic/keyvaluepair/)\<K, V\>\&) | بررسی می‌کند که مقدار خاص تهی است. [Version](../version/) برای زوج‌های کلید-مقدار. |
| static **bool** [IsNull](./isnull/)(const [System::String](../string/)\&) | بررسی می‌کند که رشته تهی است. |
| static **bool** [IsNullOrEmpty](./isnullorempty/)(const [SharedPtr](../sharedptr/)\<T\>\&) | بررسی می‌کند که مجموعه تهی یا خالی است. |
| static **bool** [IsNullOrEmpty](./isnullorempty/)(const [System::String](../string/)\&) | بررسی می‌کند که رشته تهی یا خالی است. |
## موارد مرتبط

* فضای نام [System](../)
* کتابخانه [Aspose.Slides](../../)