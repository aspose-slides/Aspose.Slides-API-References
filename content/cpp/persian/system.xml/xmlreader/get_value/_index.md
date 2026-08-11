---
title: get_Value()
second_title: Aspose.Slides برای C++: مرجع API
description: هنگامی که در یک کلاس مشتق‌شده بازنویسی شود، مقدار متنی گرهٔ فعلی را دریافت می‌کند.
type: docs
weight: 92
url: /fa/system.xml/xmlreader/get_value/
---
## XmlReader::get_Value() متد

هنگامی که در یک کلاس مشتق‌شده بازنویسی شود، مقدار متنی گرهٔ فعلی را دریافت می‌کند.

```cpp
virtual String System::Xml::XmlReader::get_Value()=0
```

### مقدار بازگشتی

مقدار بازگشتی به مقدار [XmlReader::get_NodeType](../get_nodetype/) گره بستگی دارد.

## توضیحاتی



جدول زیر انواع گره‌هایی را که دارای مقدار برای بازگشت هستند، فهرست می‌کند. همهٔ انواع گرهٔ دیگر [String::Empty](../../../system/string/empty/) را بازمی‌گردانند. 

| نوع گره | مقدار |
| --- | --- |
| `[Attribute](../../../system/attribute/)`| مقدار ویژگی. |
| `CDATA`| محتوای بخش CDATA. |
| `Comment`| محتوای کامنت. |
| `DocumentType`| زیربخش داخلی. |
| `ProcessingInstruction`| کل محتوا به‌جز هدف. |
| `SignificantWhitespace`| فضای خالی بین نشانه‌گذاری‌ها در مدل محتوای ترکیبی. |
| `[Text](../../../system.text/)`| محتوای گرهٔ متنی. |
| `Whitespace`| فضای خالی بین نشانه‌گذاری‌ها. |
| [XmlDeclaration](../../xmldeclaration/)| محتوای اعلان. |

## مراجع

* کلاس [String](../../../system/string/)
* کلاس [XmlReader](../)
* فضای‌نام [System::Xml](../../)
* کتابخانه [Aspose.Slides](../../../)