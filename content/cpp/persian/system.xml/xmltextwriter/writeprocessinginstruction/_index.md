---
title: WriteProcessingInstruction()
second_title: Aspose.Slides برای C++ مرجع API
description: "دستور پردازش را با یک فاصله بین نام و متن به صورت زیر می‌نویسید: <?name text?>."
type: docs
weight: 326
url: /fa/system.xml/xmltextwriter/writeprocessinginstruction/
---
## XmlTextWriter::WriteProcessingInstruction(String, String) متد

یک دستور پردازش را با یک فاصله بین نام و متن به صورت زیر می‌نویسد: **<?name text?>**.

```cpp
void System::Xml::XmlTextWriter::WriteProcessingInstruction(String name, String text) override
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | [String](../../../system/string/) | نام دستور پردازش. |
| text | [String](../../../system/string/) | [Text](../../../system.text/) برای گنجاندن در دستور پردازش. |
## توضیحات

این متد برای ایجاد یک اعلان XML پس از اینکه [XmlTextWriter::WriteStartDocument](../writestartdocument/) فراخوانی شده باشد، استفاده می‌شود.
## موارد مرتبط

* کلاس [String](../../../system/string/)
* کلاس [XmlTextWriter](../)
* فضای‌نام [System::Xml](../../)
* کتابخانه [Aspose.Slides](../../../)