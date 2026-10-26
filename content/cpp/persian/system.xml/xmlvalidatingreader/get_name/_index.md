---
title: get_Name()
second_title: مرجع API Aspose.Slides برای C++
description: نام کامل گرهٔ فعلی را برمی‌گرداند.
type: docs
weight: 14
url: /fa/system.xml/xmlvalidatingreader/get_name/
---
## XmlValidatingReader::get_Name() متد


نام کاملاً تعیین‌شدهٔ گرهٔ فعلی را باز می‌گرداند.

```cpp
String System::Xml::XmlValidatingReader::get_Name() override
```


### Return Value

نام کاملاً تعیین‌شدهٔ گرهٔ فعلی. به عنوان مثال، **Name** برای عنصر **<bk:book>** برابر است با **bk:book**.
## توضیحات



نام بازگردانده‌شده به XmlValidatingReader::NodeType گره وابسته است. نوع‌های گرهٔ زیر مقادیر ذکر شده را برمی‌گردانند. سایر نوع‌های گره یک رشتهٔ خالی باز می‌گردانند. 

| نوع گره | نام |
| --- | --- |
| [Attribute](../../../system/attribute/)| نام ویژگی. |
| DocumentType| نام نوع سند. |
| Element| نام برچسب. |
| EntityReference| نام موجودیتی که ارجاع داده شده. |
| ProcessingInstruction| هدف دستور پردازش. |
| [XmlDeclaration](../../xmldeclaration/)| رشتهٔ لغوی `xml`. |


## مراجع

* کلاس [String](../../../system/string/)
* کلاس [XmlValidatingReader](../)
* فضای‌نام [System::Xml](../../)
* کتابخانه [Aspose.Slides](../../../)