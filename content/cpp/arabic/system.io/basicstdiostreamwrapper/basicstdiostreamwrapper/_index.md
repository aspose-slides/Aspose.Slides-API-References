---
title: BasicSTDIOStreamWrapper()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: ينشئ مثيلاً جديدًا من BasicSTDIOStreamWrapper.
type: docs
weight: 14
url: /ar/system.io/basicstdiostreamwrapper/basicstdiostreamwrapper/
---
## BasicSTDIOStreamWrapper::BasicSTDIOStreamWrapper(std::basic_iostream\<char_type, traits_type\>\&, STDIOStreamWrappingMode, STDIOStreamPositionPreference) المُنشئ

ينشئ مثيلاً جديدًا لـ [BasicSTDIOStreamWrapper](../).

```cpp
System::IO::BasicSTDIOStreamWrapper<T, typename>::BasicSTDIOStreamWrapper(std::basic_iostream<char_type, traits_type> &str, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary, STDIOStreamPositionPreference pref_pos=STDIOStreamPositionPreference::Zero)
```

### المعاملات

| معامل | نوع | الوصف |
| --- | --- | --- |
| str | std::basic_iostream\<[char_type](../../stdiostreamwrapperbase/char_type/), [traits_type](../../stdiostreamwrapperbase/traits_type/)\>\& | إشارة إلى الدفق |
| mode | [STDIOStreamWrappingMode](../../stdiostreamwrappingmode/) | وضع التغليف |
| pref_pos | [STDIOStreamPositionPreference](../../stdiostreampositionpreference/) | الموضع الذي سيفضَّل كموضع قراءة وكتابة إذا كانا مختلفين |

## BasicSTDIOStreamWrapper::BasicSTDIOStreamWrapper(const BasicSTDIOStreamWrapper\&) المُنشئ

منشئ نسخة. محذوف.

```cpp
System::IO::BasicSTDIOStreamWrapper<T, typename>::BasicSTDIOStreamWrapper(const BasicSTDIOStreamWrapper &)=delete
```

## انظر أيضًا

* عدد [STDIOStreamWrappingMode](../../stdiostreamwrappingmode/)
* عدد [STDIOStreamPositionPreference](../../stdiostreampositionpreference/)
* تعريف نوع [char_type](../../stdiostreamwrapperbase/char_type/)
* تعريف نوع [traits_type](../../stdiostreamwrapperbase/traits_type/)
* فئة [BasicSTDIOStreamWrapper](../)
* نطاق [System::IO](../../)
* مكتبة [Aspose.Slides](../../../)