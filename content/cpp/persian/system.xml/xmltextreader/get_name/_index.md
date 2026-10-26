---
title: get_Name()
second_title: Aspose.Slides برای مرجع API C++
description: نام کامل گرهٔ فعلی را برمی‌گرداند.
type: docs
weight: 14
url: /fa/system.xml/xmltextreader/get_name/
---
## XmlTextReader::get_Name() متد

نام کامل گرهٔ فعلی را برمی‌گرداند.

```cpp
String System::Xml::XmlTextReader::get_Name() override
```

### مقدار بازگشت

نام کامل گرهٔ فعلی. به عنوان مثال، **Name** برابر **bk:book** برای عنصر **<bk:book>** است.

## توضیحات

نام بازگردانده‌شده به مقدار [XmlTextReader::get_NodeType](../get_nodetype/) گره وابسته است. انواع گرهٔ زیر مقادیر ذکر شده را برمی‌گردانند. سایر انواع گره یک رشتهٔ خالی برمی‌گردانند. 

| نوع گره | نام |
| --- | --- |
| [Attribute](../../../system/attribute/)| نام صفت. |
| DocumentType| نام نوع سند. |
| Element| نام برچسب. |
| EntityReference| نام موجودیت ارجاع‌شده. |
| ProcessingInstruction| هدف دستور پردازش. |
| [XmlDeclaration](../../xmldeclaration/)| رشتهٔ لغوی `xml`. |

## همچنین ببینید

* کلاس [String](../../../system/string/)
* کلاس [XmlTextReader](../)
* فضای‌نام [System::Xml](../../)
* کتابخانه [Aspose.Slides](../../../)