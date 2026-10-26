---
title: RemoveNamedItem()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يزيل العقدة من XmlNamedNodeMap.
type: docs
weight: 40
url: /ar/system.xml/xmlnamednodemap/removenameditem/
---
## XmlNamedNodeMap::RemoveNamedItem(String) طريقة

يزيل العقدة من [XmlNamedNodeMap](../).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::RemoveNamedItem(String name)
```

### الوسائط

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| name | [String](../../../system/string/) | الاسم المؤهل للعقدة التي سيتم إزالتها. يتم مطابقة الاسم مع قيمة [XmlNode::get_Name](../../xmlnode/get_name/) للعقدة المطابقة. |

### قيمة الإرجاع

العنصر [XmlNode](../../xmlnode/) المُزال من هذا [XmlNamedNodeMap](../) أو **nullptr** إذا لم يتم العثور على عقدة مطابقة.

## XmlNamedNodeMap::RemoveNamedItem(String, String) طريقة

يزيل عقدة ذات القيم المطابقة [XmlNode::get_LocalName](../../xmlnode/get_localname/) و[XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::RemoveNamedItem(String localName, String namespaceURI)
```

### الوسائط

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| localName | [String](../../../system/string/) | الاسم المحلي للعقدة التي سيتم إزالتها. |
| namespaceURI | [String](../../../system/string/) | معرف مساحة الاسم للعقدة التي سيتم إزالتها. |

### قيمة الإرجاع

العنصر [XmlNode](../../xmlnode/) المُزال أو **nullptr** إذا لم يتم العثور على عقدة مطابقة.

## انظر أيضًا

* نوع تعريف [SharedPtr](../../../system/sharedptr/)
* فئة [XmlNode](../../xmlnode/)
* فئة [String](../../../system/string/)
* فئة [XmlNamedNodeMap](../)
* مساحة الاسم [System::Xml](../../)
* مكتبة [Aspose.Slides](../../../)