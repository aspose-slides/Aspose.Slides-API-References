---
title: WriteRaw()
second_title: مرجع API Aspose.Slides برای C++
description: زمانی که در یک کلاس مشتق‌شده بازنویسی شود، نشانه‌گذاری خام را به صورت دستی از یک بافر کاراکتری می‌نویسد.
type: docs
weight: 287
url: /fa/system.xml/xmlwriter/writeraw/
---
## XmlWriter::WriteRaw(ArrayPtr\<char16_t\>, int32_t, int32_t) متد

هنگامی که در یک کلاس مشتق‌شده بازنویسی می‌شود، نشانه‌گذاری خام را به صورت دستی از یک بافر کاراکتری می‌نویسد.

```cpp
virtual void System::Xml::XmlWriter::WriteRaw(ArrayPtr<char16_t> buffer, int32_t index, int32_t count)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char16_t\> | آرایه‌ای از کاراکترها که متن مورد نوشتن را شامل می‌شود. |
| index | **int32_t** | موقعیت داخل بافر که آغاز متن مورد نوشتن را نشان می‌دهد. |
| count | **int32_t** | تعداد کاراکترهایی که باید نوشته شوند. |

## XmlWriter::WriteRaw(const String\&) متد

هنگامی که در یک کلاس مشتق‌شده بازنویسی می‌شود، نشانه‌گذاری خام را به صورت دستی از یک رشته می‌نویسد.

```cpp
virtual void System::Xml::XmlWriter::WriteRaw(const String &data)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| data | const [String](../../../system/string/)\& | [String](../../../system/string/) حاوی متن مورد نوشتن. |

## همچنین ببینید

* تعریف‌نوع [ArrayPtr](../../../system/arrayptr/)
* کلاس [XmlWriter](../)
* کلاس [String](../../../system/string/)
* فضای نام [System::Xml](../../)
* کتابخانه [Aspose.Slides](../../../)