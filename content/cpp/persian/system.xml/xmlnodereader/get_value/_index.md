---
title: get_Value()
second_title: Aspose.Slides برای C++ مرجع API
description: مقدار متنی گرهٔ فعلی را برمی‌گرداند.
type: docs
weight: 79
url: /fa/system.xml/xmlnodereader/get_value/
---
## XmlNodeReader::get_Value() متد

مقدار متنی گرهٔ فعلی را برمی‌گرداند.

```cpp
String System::Xml::XmlNodeReader::get_Value() override
```

### مقدار بازگشتی

مقدار برگردانده‌شده به [XmlNodeReader::get_NodeType](../get_nodetype/) گره بستگی دارد.

## ملاحظات

جدول زیر انواع گره‌هایی را که دارای مقداری برای بازگرداندن هستند، فهرست می‌کند. تمام انواع گره‌های دیگر [String::Empty](../../../system/string/empty/) را برمی‌گردانند. 

| Node Type | Value |
| --- | --- |
| [Attribute](../../../system/attribute/)| مقدار ویژگی. |
| CDATA| محتوای بخش CDATA. |
| Comment| محتوای کامنت. |
| DocumentType| زیرمجموعه داخلی. |
| ProcessingInstruction| کل محتوا، به‌جز هدف. |
| SignificantWhitespace| فاصله سفید بین نشانه‌گذاری در مدل محتوا ترکیبی. |
| [Text](../../../system.text/)| محتوای گرهٔ متنی. |
| Whitespace| فاصله سفید بین نشانه‌گذاری. |
| [XmlDeclaration](../../xmldeclaration/)| محتوای اعلام. |

## همچنین ببینید

* کلاس [String](../../../system/string/)
* کلاس [XmlNodeReader](../)
* فضای‌نام [System::Xml](../../)
* کتابخانه [Aspose.Slides](../../../)