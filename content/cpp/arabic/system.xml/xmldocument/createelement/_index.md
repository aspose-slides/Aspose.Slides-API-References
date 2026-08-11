---
title: CreateElement()
second_title: Aspose.Slides لمرجع API C++
description: ينشئ عنصرًا بالاسم المحدد.
type: docs
weight: 339
url: /ar/system.xml/xmldocument/createelement/
---
## XmlDocument::CreateElement(const String\&) طريقة

Creates an element with the specified name.

```cpp
SharedPtr<XmlElement> System::Xml::XmlDocument::CreateElement(const String &name)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | الاسم المؤهل للعنصر. إذا كان الاسم يحتوي على نقطتين فإن قيمة [XmlNode::get_Prefix](../../xmlnode/get_prefix/) تمثل الجزء من الاسم قبل النقطتين وقيمة [XmlDocument::get_LocalName](../get_localname/) تمثل الجزء من الاسم بعد النقطتين. لا يمكن أن يتضمن الاسم المؤهل بادئة **xmlns**. |

### قيمة الإرجاع

الـ [XmlElement](../../xmlelement/) الجديد.

## XmlDocument::CreateElement(const String\&, const String\&) طريقة

Creates an [XmlElement](../../xmlelement/) with the qualified name and [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
SharedPtr<XmlElement> System::Xml::XmlDocument::CreateElement(const String &qualifiedName, const String &namespaceURI)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| qualifiedName | const [String](../../../system/string/)\& | الاسم المؤهل للعنصر. إذا كان الاسم يحتوي على نقطتين فإن قيمة [XmlNode::get_Prefix](../../xmlnode/get_prefix/) ستمثل الجزء من الاسم قبل النقطتين وقيمة [XmlDocument::get_LocalName](../get_localname/) ستمثل الجزء من الاسم بعد النقطتين. لا يمكن أن يتضمن الاسم المؤهل بادئة **xmlns**. |
| namespaceURI | const [String](../../../system/string/)\& | معرف URI للمساحة الاسمية للعنصر. |

### قيمة الإرجاع

الـ [XmlElement](../../xmlelement/) الجديد.

## XmlDocument::CreateElement(const String\&, const String\&, const String\&) طريقة

Creates an element with the specified [XmlNode::get_Prefix](../../xmlnode/get_prefix/), [XmlDocument::get_LocalName](../get_localname/), and [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlElement> System::Xml::XmlDocument::CreateElement(const String &prefix, const String &localName, const String &namespaceURI)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | بادئة العنصر الجديد (إن وجدت). [String::Empty](../../../system/string/empty/) و**nullptr** متساويان. |
| localName | const [String](../../../system/string/)\& | الاسم المحلي للعنصر الجديد. |
| namespaceURI | const [String](../../../system/string/)\& | معرف URI للمساحة الاسمية للعنصر الجديد (إن وجدت). [String::Empty](../../../system/string/empty/) و**nullptr** متساويان. |

### قيمة الإرجاع

الـ [XmlElement](../../xmlelement/) الجديد.

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* الصف [XmlElement](../../xmlelement/)
* الصف [String](../../../system/string/)
* الصف [XmlDocument](../)
* النطاق [System::Xml](../../)
* Library [Aspose.Slides](../../../)