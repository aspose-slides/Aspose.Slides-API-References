---
title: get_Value()
second_title: Aspose.Slides برای C++ مرجع API
description: مقدار گره را برمی‌گرداند.
type: docs
weight: 14
url: /fa/system.xml/xmlnode/get_value/
---
## XmlNode::get_Value() method


مقدار گره را برمی‌گرداند.

```cpp
virtual String System::Xml::XmlNode::get_Value()
```


### مقدار بازگشتی

مقداری که برگردانده می‌شود بسته به [XmlNode::get_NodeType](../get_nodetype/) گره متفاوت است: 

| نوع | مقدار |
| --- | --- |
| [Attribute](../../../system/attribute/)| مقدار ویژگی. |
| CDATASection | محتوای بخش CDATA. |
| Comment | محتوای توضیح. |
| Document | `nullptr`. |
| DocumentFragment | `nullptr`. |
| DocumentType | `nullptr`. |
| Element | `nullptr`. می‌توانید از XmlElement::InnerText یا مقادیر [XmlElement::get_InnerXml](../../xmlelement/get_innerxml/) برای دسترسی به مقدار گره عنصر استفاده کنید. |
| Entity | `nullptr`. |
| EntityReference | `nullptr`. |
| Notation | `nullptr`. |
| ProcessingInstruction | تمام محتوا به‌جز هدف. |
| [Text](../../../system.text/)| محتوای گره متن. |
| SignificantWhitespace | کاراکترهای فضای خالی. فضای خالی می‌تواند شامل یک یا چند کاراکتر فاصله، بازگشت carriage، خط جدید یا تب باشد. |
| Whitespace | کاراکترهای فضای خالی. فضای خالی می‌تواند شامل یک یا چند کاراکتر فاصله، بازگشت carriage، خط جدید یا تب باشد. |
| [XmlDeclaration](../../xmldeclaration/)| محتوای اعلان (یعنی همهٔ موارد بین `<?xml` و `?>`). |

## موارد مرتبط

* کلاس [String](../../../system/string/)
* کلاس [XmlNode](../)
* فضای نام [System::Xml](../../)
* کتابخانه [Aspose.Slides](../../../)