---
title: get_Value()
second_title: مرجع API Aspose.Slides برای C++
description: مقدار متنی گرهٔ جاری را برمی‌گرداند.
type: docs
weight: 79
url: /fa/system.xml/xmlvalidatingreader/get_value/
---
## XmlValidatingReader::get_Value() متد

مقدار متنی گرهٔ جاری را برمی‌گرداند.

```cpp
String System::Xml::XmlValidatingReader::get_Value() override
```


### مقدار بازگشتی

مقدار بازگشتی بستگی به XmlValidatingReader::NodeType گره دارد.

## توضیحات

جدول زیر انواع گره‌هایی را که مقدار قابل بازگشت دارند، فهرست می‌کند. سایر انواع گره‌ها [String::Empty](../../../system/string/empty/) را برمی‌گردانند. 

| نوع گره | مقدار |
| --- | --- |
| [Attribute](../../../system/attribute/)| مقدار ویژگی. |
| CDATA| محتوای بخش CDATA. |
| Comment| محتوای کامنت. |
| DocumentType| زیرمجموعه داخلی. |
| ProcessingInstruction| تمام محتوا، به‌جز هدف. |
| SignificantWhitespace| فاصله سفید بین نشانه‌گذاری در یک مدل محتوای ترکیبی. |
| [Text](../../../system.text/)| محتوای گره متن. |
| Whitespace| فاصله سفید بین نشانه‌گذاری. |
| [XmlDeclaration](../../xmldeclaration/)| محتوای اعلان. |


## موارد مرتبط

* کلاس [String](../../../system/string/)
* کلاس [XmlValidatingReader](../)
* فضای نام [System::Xml](../../)
* کتابخانه [Aspose.Slides](../../../)