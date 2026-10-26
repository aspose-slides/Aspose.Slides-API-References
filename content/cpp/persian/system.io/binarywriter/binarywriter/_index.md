---
title: BinaryWriter()
second_title: مرجع API Aspose.Slides برای C++
description: یک نمونه از کلاس BinaryWriter ایجاد می‌کند که داده‌ها را با استفاده از رمزگذاری مشخص به جریان تعیین‌شده می‌نویسد.
type: docs
weight: 1
url: /fa/system.io/binarywriter/binarywriter/
---
## BinaryWriter::BinaryWriter(const StreamPtr\&, const EncodingPtr\&, bool) سازنده

یک نمونه از کلاس [BinaryWriter](../) که داده‌ها را با استفاده از رمزگذاری مشخص به جریان داده شده می‌نویسد، می‌سازد.

```cpp
System::IO::BinaryWriter::BinaryWriter(const StreamPtr &stream, const EncodingPtr &encoding=System::Text::Encoding::get_UTF8Unmarked(), bool leaveopen=false)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | جریان خروجی |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | رمزگذاری مورد استفاده |
| leaveopen | **bool** | مشخص می‌کند که آیا جریان **stream** بعد از از بین رفتن شیء فعلی باز بماند (true) یا نه (false) |

## موارد مرتبط

* تعریف نوع [StreamPtr](../../../system/streamptr/)
* تعریف نوع [EncodingPtr](../../../system/encodingptr/)
* کلاس [BinaryWriter](../)
* فضای‌نام [System::IO](../../)
* کتابخانه [Aspose.Slides](../../../)