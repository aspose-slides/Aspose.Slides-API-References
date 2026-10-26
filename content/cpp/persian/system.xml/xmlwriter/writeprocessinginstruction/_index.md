---
title: WriteProcessingInstruction()
second_title: Aspose.Slides برای مرجع API C++
description: "هنگامی که در یک کلاس مشتق‌شده بازنویسی می‌شود، یک دستور پردازشی را با یک فاصله بین نام و متن به شکل زیر می‌نویسد: <?name text?>."
type: docs
weight: 196
url: /fa/system.xml/xmlwriter/writeprocessinginstruction/
---
## XmlWriter::WriteProcessingInstruction(String, String) متد

هنگامی که در یک کلاس مشتق‌شده بازنویسی می‌شود، یک دستور پردازشی را با یک فضای بین نام و متن به صورت زیر می‌نویسد: **<?name text?>**.

```cpp
virtual void System::Xml::XmlWriter::WriteProcessingInstruction(String name, String text)=0
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | [String](../../../system/string/) | نام دستور پردازشی. |
| text | [String](../../../system/string/) | متنی که باید در دستور پردازشی گنجانده شود. |
## توضیحات

این متد برای ایجاد یک اعلان XML پس از اینکه [XmlWriter::WriteStartDocument](../writestartdocument/) قبلاً فراخوانی شده است، استفاده می‌شود.
## مراجع

* کلاس [String](../../../system/string/)
* کلاس [XmlWriter](../)
* فضای نام [System::Xml](../../)
* کتابخانه [Aspose.Slides](../../../)