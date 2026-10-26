---
title: GetNamedItem()
second_title: مرجع API Aspose.Slides للغة C++
description: يسترجع XmlNode المحدد بالاسم.
type: docs
weight: 14
url: /ar/system.xml/xmlnamednodemap/getnameditem/
---
## XmlNamedNodeMap::GetNamedItem(String) طريقة

يسترجع [XmlNode](../../xmlnode/) المحددة بالاسم.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::GetNamedItem(String name)
```

### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | الاسم المؤهل للعقدة المراد استرجاعها. يتم مطابقته مع قيمة [XmlNode::get_Name](../../xmlnode/get_name/) للعقدة المطابقة. |

### قيمة الإرجاع

كائن [XmlNode](../../xmlnode/) بالاسم المحدد أو **nullptr** إذا لم يتم العثور على عقدة مطابقة.

## XmlNamedNodeMap::GetNamedItem(String, String) طريقة

يسترجع عقدة ذات القيم [XmlNode::get_LocalName](../../xmlnode/get_localname/) و [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) المطابقة.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::GetNamedItem(String localName, String namespaceURI)
```

### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | الاسم المحلي للعقدة المراد استرجاعها. |
| namespaceURI | [String](../../../system/string/) | معرف المورد الموحد (URI) للمساحة الاسمية للعقدة المراد استرجاعها. |

### قيمة الإرجاع

كائن [XmlNode](../../xmlnode/) بالاسم المحلي ومعرف المورد الموحد للمساحة الاسمية المطابقين أو **nullptr** إذا لم يتم العثور على عقدة مطابقة.

## راجع أيضًا

* إعادة تعريف [SharedPtr](../../../system/sharedptr/)
* فئة [XmlNode](../../xmlnode/)
* فئة [String](../../../system/string/)
* فئة [XmlNamedNodeMap](../)
* مساحة اسم [System::Xml](../../)
* مكتبة [Aspose.Slides](../../../)