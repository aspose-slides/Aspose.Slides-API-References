---
title: BasicSTDIOStreamWrapper()
second_title: مرجع API Aspose.Slides برای C++
description: یک نمونه جدید از BasicSTDIOStreamWrapper را می‌سازد.
type: docs
weight: 14
url: /fa/system.io/basicstdiostreamwrapper/basicstdiostreamwrapper/
---
## BasicSTDIOStreamWrapper::BasicSTDIOStreamWrapper(std::basic_iostream\<char_type, traits_type\>\&, STDIOStreamWrappingMode, STDIOStreamPositionPreference) سازنده

یک نمونه جدید از [BasicSTDIOStreamWrapper](../) را می‌سازد.

```cpp
System::IO::BasicSTDIOStreamWrapper<T, typename>::BasicSTDIOStreamWrapper(std::basic_iostream<char_type, traits_type> &str, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary, STDIOStreamPositionPreference pref_pos=STDIOStreamPositionPreference::Zero)
```

### آرگومان‌ها

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| str | std::basic_iostream\<[char_type](../../stdiostreamwrapperbase/char_type/), [traits_type](../../stdiostreamwrapperbase/traits_type/)\>\& | مرجع به استریم |
| mode | [STDIOStreamWrappingMode](../../stdiostreamwrappingmode/) | حالت بسته‌بندی |
| pref_pos | [STDIOStreamPositionPreference](../../stdiostreampositionpreference/) | موقعیتی که به‌عنوان موقعیت خواندن و نوشتن ترجیح داده می‌شود، اگر متفاوت باشند |

## BasicSTDIOStreamWrapper::BasicSTDIOStreamWrapper(const BasicSTDIOStreamWrapper\&) سازنده

سازنده کپی. حذف شده.

```cpp
System::IO::BasicSTDIOStreamWrapper<T, typename>::BasicSTDIOStreamWrapper(const BasicSTDIOStreamWrapper &)=delete
```

## موارد مرتبط

* enum [STDIOStreamWrappingMode](../../stdiostreamwrappingmode/)
* enum [STDIOStreamPositionPreference](../../stdiostreampositionpreference/)
* typedef [char_type](../../stdiostreamwrapperbase/char_type/)
* typedef [traits_type](../../stdiostreamwrapperbase/traits_type/)
* class [BasicSTDIOStreamWrapper](../)
* namespace [System::IO](../../)
* library [Aspose.Slides](../../../)