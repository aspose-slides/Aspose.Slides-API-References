---
title: CreateNode()
second_title: مرجع API Aspose.Slides برای C++
description: "یک XmlNode را با XmlNodeType، XmlNode::get_Prefix، XmlDocument::get_Name و XmlNode::get_NamespaceURI مشخص شده ایجاد می‌کند."
type: docs
weight: 482
url: /fa/system.xml/xmldocument/createnode/
---
## XmlDocument::CreateNode(XmlNodeType, const String\&, const String\&, const String\&) متد

یک [XmlNode](../../xmlnode/) با XmlNodeType مشخص شده، [XmlNode::get_Prefix](../../xmlnode/get_prefix/)، [XmlDocument::get_Name](../get_name/) و [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) ایجاد می‌کند.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::CreateNode(XmlNodeType type, const String &prefix, const String &name, const String &namespaceURI)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| type | [XmlNodeType](../../xmlnodetype/) | XmlNodeType گره جدید. |
| prefix | const [String](../../../system/string/)\& | پیشوند گره جدید. |
| name | const [String](../../../system/string/)\& | نام محلی گره جدید. |
| namespaceURI | const [String](../../../system/string/)\& | URI فضای نام گره جدید. |

### مقدار بازگشت

[XmlNode](../../xmlnode/) جدید.

## XmlDocument::CreateNode(const String\&, const String\&, const String\&) متد

یک [XmlNode](../../xmlnode/) با نوع گره مشخص شده، [XmlDocument::get_Name](../get_name/) و [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) ایجاد می‌کند.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::CreateNode(const String &nodeTypeString, const String &name, const String &namespaceURI)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| nodeTypeString | const [String](../../../system/string/)\& | [String](../../../system/string/) نسخه از XmlNodeType گره جدید. این پارامتر باید یکی از مقادیر جدول زیر باشد. |
| name | const [String](../../../system/string/)\& | نام کامل گره جدید. اگر نام شامل دو نقطه باشد، به اجزای [XmlNode::get_Prefix](../../xmlnode/get_prefix/) و [XmlDocument::get_LocalName](../get_localname/) تجزیه می‌شود. |
| namespaceURI | const [String](../../../system/string/)\& | URI فضای نام گره جدید. |

### مقدار بازگشت

[XmlNode](../../xmlnode/) جدید.

## توضیحات

پارامتر **nodeTypeString** به حروف کوچک و بزرگ حساس است و باید یکی از مقادیر جدول زیر باشد:

| nodeTypeString| XmlNodeType |
| --- | --- |
| attribute| [Attribute](../../../system/attribute/)|
| cdatasection| CDATA |
| comment| Comment |
| document| Document |
| documentfragment| DocumentFragment |
| documenttype| DocumentType |
| element| Element |
| entityreference| EntityReference |
| processinginstruction| ProcessingInstruction |
| significantwhitespace| SignificantWhitespace |
| text| [Text](../../../system.text/)|
| whitespace| Whitespace |

## XmlDocument::CreateNode(XmlNodeType, const String\&, const String\&) متد

یک [XmlNode](../../xmlnode/) با XmlNodeType مشخص شده، [XmlDocument::get_Name](../get_name/) و [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) ایجاد می‌کند.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::CreateNode(XmlNodeType type, const String &name, const String &namespaceURI)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| type | [XmlNodeType](../../xmlnodetype/) | XmlNodeType گره جدید. |
| name | const [String](../../../system/string/)\& | نام کامل گره جدید. اگر نام شامل دو نقطه باشد، به اجزای [XmlNode::get_Prefix](../../xmlnode/get_prefix/) و [XmlDocument::get_LocalName](../get_localname/) تجزیه می‌شود. |
| namespaceURI | const [String](../../../system/string/)\& | URI فضای نام گره جدید. |

### مقدار بازگشت

[XmlNode](../../xmlnode/) جدید.

## مراجع

* Enum [XmlNodeType](../../xmlnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [String](../../../system/string/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)