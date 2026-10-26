---
title: GetElementsByTagName()
second_title: Aspose.Slides – مرجع API للغة C++
description: ترجع XmlNodeList تحتوي على قائمة بجميع العناصر الفرعية التي تطابق الاسم المحدد.
type: docs
weight: 443
url: /ar/system.xml/xmldocument/getelementsbytagname/
---
## XmlDocument::GetElementsByTagName(String) طريقة

إرجاع [XmlNodeList](../../xmlnodelist/) يحتوي على قائمة بجميع العناصر الفرعية التي تطابق الاسم المحدد.

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlDocument::GetElementsByTagName(String name)
```

### المعاملات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| name | [String](../../../system/string/) | الاسم المؤهل للمطابقة. يتم مطابقته مع قيمة **get_Name** للعقدة المطابقة. القيمة الخاصة **"*"`** تطابق جميع الوسوم. |

### القيمة المرجعة

حاوية [XmlNodeList](../../xmlnodelist/) تحتوي على قائمة بجميع العقد المطابقة. إذا لم تطابق أي عقدة **name**، فستكون المجموعة المرتجعة فارغة.

## XmlDocument::GetElementsByTagName(String, String) طريقة

إرجاع [XmlNodeList](../../xmlnodelist/) يحتوي على قائمة بجميع العناصر الفرعية التي تطابق [XmlDocument::get_LocalName](../get_localname/) و [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) المحددين.

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlDocument::GetElementsByTagName(String localName, String namespaceURI)
```

### المعاملات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| localName | [String](../../../system/string/) | الاسم المحلي للمطابقة. القيمة الخاصة **"*"`** تطابق جميع الوسوم. |
| namespaceURI | [String](../../../system/string/) | NamespaceURI للمطابقة. |

### القيمة المرجعة

حاوية [XmlNodeList](../../xmlnodelist/) تحتوي على قائمة بجميع العقد المطابقة. إذا لم تطابق أي عقدة **localName** و **namespaceURI** المحددين، فستكون المجموعة المرتجعة فارغة.

## انظر أيضا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [XmlNodeList](../../xmlnodelist/)
* فئة [String](../../../system/string/)
* فئة [XmlDocument](../)
* نطاق [System::Xml](../../)
* مكتبة [Aspose.Slides](../../../)