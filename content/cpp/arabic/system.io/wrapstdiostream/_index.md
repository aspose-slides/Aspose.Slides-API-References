---
title: WrapSTDIOStream()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "دالة غلاف لتدفقات شبيهة بـ std::basic_istream."
type: docs
weight: 469
url: /ar/system.io/wrapstdiostream/
---
## System::IO::WrapSTDIOStream(std::basic_istream\<char_type, traits_type\>\&, STDIOStreamWrappingMode) دالة

دالة غلاف لتدفقات شبيهة بـ std::basic_istream.

```cpp
template<typename char_type,typename traits_type> SharedPtr<Stream> System::IO::WrapSTDIOStream(std::basic_istream<char_type, traits_type> &stream, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | std::basic_istream\<char_type, traits_type\>\& | تدفق شبيه بـ std::basic_istream |
| mode | [STDIOStreamWrappingMode](../stdiostreamwrappingmode/) | وضع التغليف |

### قيمة الإرجاع

[BasicSTDIStreamWrapper](../basicstdistreamwrapper/) غلاف

## System::IO::WrapSTDIOStream(std::basic_ostream\<char_type, traits_type\>\&, STDIOStreamWrappingMode) دالة

دالة غلاف لتدفقات شبيهة بـ std::basic_ostream.

```cpp
template<typename char_type,typename traits_type> SharedPtr<Stream> System::IO::WrapSTDIOStream(std::basic_ostream<char_type, traits_type> &stream, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | std::basic_ostream\<char_type, traits_type\>\& | تدفق شبيه بـ std::basic_ostream |
| mode | [STDIOStreamWrappingMode](../stdiostreamwrappingmode/) | وضع التغليف |

### قيمة الإرجاع

[BasicSTDOStreamWrapper](../basicstdostreamwrapper/) غلاف

## System::IO::WrapSTDIOStream(std::basic_iostream\<char_type, traits_type\>\&, STDIOStreamWrappingMode, STDIOStreamPositionPreference) دالة

دالة غلاف لتدفقات شبيهة بـ std::basic_iostream.

```cpp
template<typename char_type,typename traits_type> SharedPtr<Stream> System::IO::WrapSTDIOStream(std::basic_iostream<char_type, traits_type> &stream, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary, STDIOStreamPositionPreference pref_pos=STDIOStreamPositionPreference::Zero)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | std::basic_iostream\<char_type, traits_type\>\& | تدفق شبيه بـ std::basic_iostream |
| mode | [STDIOStreamWrappingMode](../stdiostreamwrappingmode/) | وضع التغليف |
| pref_pos | [STDIOStreamPositionPreference](../stdiostreampositionpreference/) | الموضع الذي سيُفضَّل كموضع قراءة وكتابة، إذا كانا مختلفين |

### قيمة الإرجاع

[BasicSTDIOStreamWrapper](../basicstdiostreamwrapper/) غلاف

## انظر أيضاً

* Enum [STDIOStreamWrappingMode](../stdiostreamwrappingmode/)
* Enum [STDIOStreamPositionPreference](../stdiostreampositionpreference/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Class [Stream](../stream/)
* Namespace [System::IO](../)
* Library [Aspose.Slides](../../)