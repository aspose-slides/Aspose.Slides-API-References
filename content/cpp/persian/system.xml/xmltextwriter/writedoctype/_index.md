---
title: WriteDocType()
second_title: Aspose.Slides برای مرجع API C++
description: بیانیه DOCTYPE را با نام مشخص شده و ویژگی‌های اختیاری می‌نویسد.
type: docs
weight: 222
url: /fa/system.xml/xmltextwriter/writedoctype/
---
## XmlTextWriter::WriteDocType(const String\&, const String\&, const String\&, const String\&) متد

بیانیه DOCTYPE را با نام مشخص شده و ویژگی‌های اختیاری می‌نویسد.

```cpp
void System::Xml::XmlTextWriter::WriteDocType(const String &name, const String &pubid, const String &sysid, const String &subset) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | نام DOCTYPE. این مقدار باید خالی نباشد. |
| pubid | const [String](../../../system/string/)\& | اگر مقدار غیر تهی باشد، همچنین PUBLIC "pubid" "sysid" را می‌نویسد که در آن **pubid** و **sysid** با مقدار آرگومان‌های داده‌شده جایگزین می‌شوند. |
| sysid | const [String](../../../system/string/)\& | اگر **pubid** تهی باشد و **sysid** غیر تهی باشد، SYSTEM "sysid" را می‌نویسد که در آن **sysid** با مقدار این آرگومان جایگزین می‌شود. |
| subset | const [String](../../../system/string/)\& | اگر غیر تهی باشد، [subset] را می‌نویسد که در آن subset با مقدار این آرگومان جایگزین می‌شود. |

## همچنین ببینید

* کلاس [String](../../../system/string/)
* کلاس [XmlTextWriter](../)
* فضای‌نام [System::Xml](../../)
* کتابخانه [Aspose.Slides](../../../)