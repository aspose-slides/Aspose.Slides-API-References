---
title: CreateNode()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "ينشئ XmlNode باستخدام XmlNodeType المحدد، XmlNode::get_Prefix، XmlDocument::get_Name، و XmlNode::get_NamespaceURI."
type: docs
weight: 482
url: /ar/system.xml/xmldocument/createnode/
---
## XmlDocument::CreateNode(XmlNodeType, const String\&, const String\&, const String\&) طريقة

ينشئ [XmlNode](../../xmlnode/) باستخدام XmlNodeType المحدد، [XmlNode::get_Prefix](../../xmlnode/get_prefix/)، [XmlDocument::get_Name](../get_name/)، و[XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::CreateNode(XmlNodeType type, const String &prefix, const String &name, const String &namespaceURI)
```

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| type | [XmlNodeType](../../xmlnodetype/) | XmlNodeType للعنصر الجديد. |
| prefix | const [String](../../../system/string/)\& | البادئة للعنصر الجديد. |
| name | const [String](../../../system/string/)\& | الاسم المحلي للعنصر الجديد. |
| namespaceURI | const [String](../../../system/string/)\& | URI مساحة الاسم للعنصر الجديد. |

### قيمة الإرجاع

[XmlNode](../../xmlnode/) الجديد.

## XmlDocument::CreateNode(const String\&, const String\&, const String\&) طريقة

ينشئ [XmlNode](../../xmlnode/) باستخدام نوع العقدة المحدد، [XmlDocument::get_Name](../get_name/)، و[XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::CreateNode(const String &nodeTypeString, const String &name, const String &namespaceURI)
```

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| nodeTypeString | const [String](../../../system/string/)\& | نسخة [String](../../../system/string/) من XmlNodeType للعنصر الجديد. يجب أن تكون هذه المعلمة أحد القيم المذكورة في الجدول أدناه. |
| name | const [String](../../../system/string/)\& | الاسم المؤهل للعنصر الجديد. إذا كان الاسم يحتوي على نقطتين، يتم تحليله إلى مكوّنات [XmlNode::get_Prefix](../../xmlnode/get_prefix/) و[XmlDocument::get_LocalName](../get_localname/). |
| namespaceURI | const [String](../../../system/string/)\& | URI مساحة الاسم للعنصر الجديد. |

### قيمة الإرجاع

[XmlNode](../../xmlnode/) الجديد.

## ملاحظات

معلمة **nodeTypeString** حساسة لحالة الأحرف ويجب أن تكون واحدة من القيم في الجدول التالي:

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

## XmlDocument::CreateNode(XmlNodeType, const String\&, const String\&) طريقة

ينشئ [XmlNode](../../xmlnode/) باستخدام XmlNodeType المحدد، [XmlDocument::get_Name](../get_name/)، و[XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::CreateNode(XmlNodeType type, const String &name, const String &namespaceURI)
```

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| type | [XmlNodeType](../../xmlnodetype/) | XmlNodeType للعنصر الجديد. |
| name | const [String](../../../system/string/)\& | الاسم المؤهل للعنصر الجديد. إذا كان الاسم يحتوي على نقطتين فإنه يُحلل إلى مكوّنات [XmlNode::get_Prefix](../../xmlnode/get_prefix/) و[XmlDocument::get_LocalName](../get_localname/). |
| namespaceURI | const [String](../../../system/string/)\& | URI مساحة الاسم للعنصر الجديد. |

### قيمة الإرجاع

[XmlNode](../../xmlnode/) الجديد.

## انظر أيضًا

* Enum [XmlNodeType](../../xmlnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [XmlNode](../../xmlnode/)
* فئة [String](../../../system/string/)
* فئة [XmlDocument](../)
* مساحة اسم [System::Xml](../../)
* Library [Aspose.Slides](../../../)