---
title: WrapSTDIOStream()
second_title: "مرجع API Aspose.Slides برای C++"
description: "تابع پوشاننده برای جریان‌های شبیه std::basic_istream."
type: docs
weight: 469
url: /fa/system.io/wrapstdiostream/
---
## System::IO::WrapSTDIOStream(std::basic_istream\<char_type, traits_type\>\&, STDIOStreamWrappingMode) function

تابع پوشاننده برای جریان‌های شبیه std::basic_istream.

```cpp
template<typename char_type,typename traits_type> SharedPtr<Stream> System::IO::WrapSTDIOStream(std::basic_istream<char_type, traits_type> &stream, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | std::basic_istream\<char_type, traits_type\>\& | جریان شبیه std::basic_istream |
| mode | [STDIOStreamWrappingMode](../stdiostreamwrappingmode/) | حالت بسته‌بندی |

### مقدار بازگشتی

[BasicSTDIStreamWrapper](../basicstdistreamwrapper/) wrapper

## System::IO::WrapSTDIOStream(std::basic_ostream\<char_type, traits_type\>\&, STDIOStreamWrappingMode) function

تابع پوشاننده برای جریان‌های شبیه std::basic_ostream.

```cpp
template<typename char_type,typename traits_type> SharedPtr<Stream> System::IO::WrapSTDIOStream(std::basic_ostream<char_type, traits_type> &stream, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | std::basic_ostream\<char_type, traits_type\>\& | جریان شبیه std::basic_ostream |
| mode | [STDIOStreamWrappingMode](../stdiostreamwrappingmode/) | حالت بسته‌بندی |

### مقدار بازگشتی

[BasicSTDOStreamWrapper](../basicstdostreamwrapper/) wrapper

## System::IO::WrapSTDIOStream(std::basic_iostream\<char_type, traits_type\>\&, STDIOStreamWrappingMode, STDIOStreamPositionPreference) function

تابع پوشاننده برای جریان‌های شبیه std::basic_iostream.

```cpp
template<typename char_type,typename traits_type> SharedPtr<Stream> System::IO::WrapSTDIOStream(std::basic_iostream<char_type, traits_type> &stream, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary, STDIOStreamPositionPreference pref_pos=STDIOStreamPositionPreference::Zero)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | std::basic_iostream\<char_type, traits_type\>\& | جریان شبیه std::basic_iostream |
| mode | [STDIOStreamWrappingMode](../stdiostreamwrappingmode/) | حالت بسته‌بندی |
| pref_pos | [STDIOStreamPositionPreference](../stdiostreampositionpreference/) | موقعیتی که به عنوان موقعیت خواندن و نوشتن ترجیح داده می‌شود، در صورت متفاوت بودن |

### مقدار بازگشتی

[BasicSTDIOStreamWrapper](../basicstdiostreamwrapper/) wrapper

## موارد مرتبط

* Enum [STDIOStreamWrappingMode](../stdiostreamwrappingmode/)
* Enum [STDIOStreamPositionPreference](../stdiostreampositionpreference/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Class [Stream](../stream/)
* Namespace [System::IO](../)
* Library [Aspose.Slides](../../)