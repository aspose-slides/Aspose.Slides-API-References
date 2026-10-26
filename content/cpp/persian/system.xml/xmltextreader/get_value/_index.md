---
title: get_Value()
second_title: Aspose.Slides برای مرجع API C++
description: مقدار متنی گره فعلی را برمی‌گرداند.
type: docs
weight: 79
url: /fa/system.xml/xmltextreader/get_value/
---
## XmlTextReader::get_Value() متد

مقدار متنی گره فعلی را برمی‌گرداند.

```cpp
String System::Xml::XmlTextReader::get_Value() override
```

### مقدار بازگشت

مقدار برگردانده شده به مقدار [XmlTextReader::get_NodeType](../get_nodetype/) گره بستگی دارد.

## توضیحات

جدول زیر انواع گره‌هایی که دارای مقداری برای بازگشت هستند را فهرست می‌کند. تمام انواع گره دیگر [String::Empty](../../../system/string/empty/) را باز می‌گردانند.

| نوع گره | مقدار |
| --- | --- |
| [Attribute](../../../system/attribute/)| مقدار ویژگی. |
| CDATA| محتوای بخش CDATA. |
| Comment| محتوای کامنت. |
| DocumentType| زیرمجموعه داخلی. |
| ProcessingInstruction| کل محتوا به‌استثنای هدف. |
| SignificantWhitespace| فضای خالی داخل محدوده `xml:space='preserve'`. |
| [Text](../../../system.text/)| محتوای گره متنی. |
| Whitespace| فضای خالی بین نشانه‌گذاری. |
| [XmlDeclaration](../../xmldeclaration/)| محتوای اعلان. |

## موارد مرتبط

* کلاس [String](../../../system/string/)
* کلاس [XmlTextReader](../)
* فضای نام [System::Xml](../../)
* کتابخانه [Aspose.Slides](../../../)