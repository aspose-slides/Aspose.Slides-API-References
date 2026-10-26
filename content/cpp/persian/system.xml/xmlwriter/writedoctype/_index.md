---
title: WriteDocType()
second_title: مرجع API Aspose.Slides برای C++
description: هنگامی که در یک کلاس مشتق شده بازنویسی شود، اعلان DOCTYPE را با نام مشخص شده و ویژگی‌های اختیاری می‌نویسد.
type: docs
weight: 79
url: /fa/system.xml/xmlwriter/writedoctype/
---
## XmlWriter::WriteDocType(const String&, const String&, const String&, const String&) متد


زمانی که در یک کلاس مشتق شده بازنویسی شود، اعلان DOCTYPE را با نام مشخص شده و ویژگی‌های اختیاری می‌نویسد.

```cpp
virtual void System::Xml::XmlWriter::WriteDocType(const String &name, const String &pubid, const String &sysid, const String &subset)=0
```


### پارامترها
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | const [String](../../../system/string/)& | نام DOCTYPE. این باید خالی نباشد. |
| pubid | const [String](../../../system/string/)& | اگر مقدار غیر-null باشد، همچنین PUBLIC "pubid" "sysid" را می‌نویسد که در آن **pubid** و **sysid** با مقدار آرگومان‌های داده شده جایگزین می‌شوند. |
| sysid | const [String](../../../system/string/)& | اگر **pubid** برابر **nullptr** باشد و **sysid** غیر-null باشد، SYSTEM "sysid" را می‌نویسد که در آن **sysid** با مقدار این آرگومان جایگزین می‌شود. |
| subset | const [String](../../../system/string/)& | اگر غیر-null باشد، [subset] را می‌نویسد که در آن subset با مقدار این آرگومان جایگزین می‌شود. |

## موارد مرتبط

* کلاس [String](../../../system/string/)
* کلاس [XmlWriter](../)
* فضای‌نام [System::Xml](../../)
* کتابخانه [Aspose.Slides](../../../)