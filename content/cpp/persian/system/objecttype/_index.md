---
title: ObjectType
second_title: مرجع API Aspose.Slides برای C++
description: متدهای ایستا را که گیتِرهای نوع شیء را پیاده‌سازی می‌کنند فراهم می‌کند. این یک نوع ایستا بدون سرویس‌های نمونه است. شما هرگز نباید به هیچ روشی نمونه‌ای از آن ایجاد کنید.
type: docs
weight: 1158
url: /fa/system/objecttype/
---
## ObjectType کلاس

متدهای ایستا را که گیتِرهای نوع شیء را پیاده‌سازی می‌کنند فراهم می‌کند. این یک نوع ایستا بدون سرویس‌های نمونه است. شما هرگز نباید به هیچ روشی نمونه‌ای از آن ایجاد کنید.

```cpp
class ObjectType
```

## متدها

| متد | توضیح |
| --- | --- |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T\&) | ترجمه typeof() را پیاده‌سازی می‌کند. بارگذاری مجدد برای اشاره‌گرهای هوشمند. |
| static std::enable_if<\![IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value\&&\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T\&) | ترجمه typeof() را پیاده‌سازی می‌کند. بارگذاری مجدد برای ساختارها. |
| static std::enable_if\<[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T\&) | ترجمه typeof() را پیاده‌سازی می‌کند. بارگذاری مجدد برای استثناها. |
| static std::enable_if\<std::is_fundamental\<T\>::value||std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T) | ترجمه typeof() را پیاده‌سازی می‌کند. بارگذاری مجدد برای انواع ابتدایی. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T) | ترجمه typeof() را پیاده‌سازی می‌کند. بارگذاری مجدد برای انواع [Nullable](../nullable/). |
| static std::enable_if\<std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | ترجمه typeof() را پیاده‌سازی می‌کند. بارگذاری مجدد برای انواع ابتدایی. |
| static std::enable_if\<std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | ترجمه typeof() را پیاده‌سازی می‌کند. بارگذاری مجدد برای انواع شمارشی. |
| static std::enable_if<(\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&\![IsBoxable](../isboxable/)\<T\>::value)||[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | ترجمه typeof() را پیاده‌سازی می‌کند. بارگذاری مجدد برای ساختارها و اشاره‌گرها. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | ترجمه typeof() را پیاده‌سازی می‌کند. بارگذاری مجدد برای [Nullable](../nullable/). |
| static std::enable_if\<detail::is_a\<T, MulticastDelegate\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | ترجمه typeof() را پیاده‌سازی می‌کند. بارگذاری مجدد برای MutlicastDelegate. |
| static std::enable_if<\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&[IsBoxable](../isboxable/)\<T\>::value\&&\!detail::is_a\<T, MulticastDelegate\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | ترجمه typeof() را پیاده‌سازی می‌کند. بارگذاری مجدد برای ساختارها و اشاره‌گرها. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)(const [String](../string/)\&) | ترجمه typeof() را پیاده‌سازی می‌کند. بارگذاری مجدد برای نوع رشته. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | ترجمه typeof() را پیاده‌سازی می‌کند. بارگذاری مجدد برای **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | ترجمه typeof() را پیاده‌سازی می‌کند. بارگذاری مجدد برای **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | ترجمه typeof() را پیاده‌سازی می‌کند. بارگذاری مجدد برای **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | ترجمه typeof() را پیاده‌سازی می‌کند. بارگذاری مجدد برای **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | ترجمه typeof() را پیاده‌سازی می‌کند. بارگذاری مجدد برای **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | ترجمه typeof() را پیاده‌سازی می‌کند. بارگذاری مجدد برای **uint8_t**. |

## موارد مرتبط

* فضای‌نام [System](../)
* کتابخانه [Aspose.Slides](../../)