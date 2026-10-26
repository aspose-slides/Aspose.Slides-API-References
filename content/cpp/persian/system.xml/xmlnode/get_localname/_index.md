---
title: get_LocalName()
second_title: Aspose.Slides برای مرجع API C++
description: نام محلی گره را برمی‌گرداند، زمانی که در یک کلاس مشتق شده بازنویسی شود.
type: docs
weight: 209
url: /fa/system.xml/xmlnode/get_localname/
---
## XmlNode::get_LocalName() متد

نام محلی گره را باز می‌گرداند، زمانی که در یک کلاس مشتق شده بازنویسی شود.

```cpp
virtual String System::Xml::XmlNode::get_LocalName()=0
```


### مقدار بازگشتی

نام گره بدون پیشوند. به عنوان مثال، **LocalName** برابر **book** برای عنصر **<bk:book>** است.

## ملاحظات

نام بازگردانده شده به [XmlNode::get_NodeType](../get_nodetype/) گره بستگی دارد:

| نوع | نام |
| --- | --- |
| [Attribute](../../../system/attribute/)| نام محلی ویژگی. |
| CDATA | #cdata-section |
| Comment | #comment |
| Document | #document |
| DocumentFragment | #document-fragment |
| DocumentType | نام نوع سند. |
| Element | نام محلی عنصر. |
| Entity | نام موجودیت. |
| EntityReference | نام موجودیتی که ارجاع داده شده است. |
| Notation | نام نماد. |
| ProcessingInstruction | هدف دستور پردازش. |
| [Text](../../../system.text/)| #text |
| Whitespace | #whitespace |
| SignificantWhitespace | #significant-whitespace |
| [XmlDeclaration](../../xmldeclaration/)| #xml-declaration |


## همچنین ببینید

* کلاس [String](../../../system/string/)
* کلاس [XmlNode](../)
* فضای نام [System::Xml](../../)
* کتابخانه [Aspose.Slides](../../../)