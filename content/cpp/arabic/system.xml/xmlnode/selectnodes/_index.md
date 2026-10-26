---
title: SelectNodes()
second_title: Aspose.Slides لـ C++ مرجع واجهة برمجة التطبيقات
description: يقوم بتحديد قائمة من العقد التي تتطابق مع تعبير XPath.
type: docs
weight: 365
url: /ar/system.xml/xmlnode/selectnodes/
---
## XmlNode::SelectNodes(const String\&) طريقة

يحدد قائمة من العقد التي تطابق التعبير [XPath](../../../system.xml.xpath/).

```cpp
SharedPtr<XmlNodeList> System::Xml::XmlNode::SelectNodes(const String &xpath)
```

### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | التعبير [XPath](../../../system.xml.xpath/). |

### قيمة الإرجاع

[XmlNodeList](../../xmlnodelist/) يحتوي على مجموعة من العقد التي تطابق الاستعلام [XPath](../../../system.xml.xpath/).

## XmlNode::SelectNodes(const String\&, const SharedPtr\<XmlNamespaceManager\>\&) طريقة

يحدد قائمة من العقد التي تطابق التعبير [XPath](../../../system.xml.xpath/). يتم حل أي بادئات موجودة في التعبير [XPath](../../../system.xml.xpath/) باستخدام [XmlNamespaceManager](../../xmlnamespacemanager/) المقدم.

```cpp
SharedPtr<XmlNodeList> System::Xml::XmlNode::SelectNodes(const String &xpath, const SharedPtr<XmlNamespaceManager> &nsmgr)
```

### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | التعبير [XPath](../../../system.xml.xpath/). |
| nsmgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | [XmlNamespaceManager](../../xmlnamespacemanager/) لاستخدامه في حل مساحات الأسماء للبادئات في التعبير [XPath](../../../system.xml.xpath/). |

### قيمة الإرجاع

[XmlNodeList](../../xmlnodelist/) يحتوي على مجموعة من العقد التي تطابق الاستعلام [XPath](../../../system.xml.xpath/).

## انظر أيضا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [XmlNodeList](../../xmlnodelist/)
* فئة [String](../../../system/string/)
* فئة [XmlNode](../)
* فئة [XmlNamespaceManager](../../xmlnamespacemanager/)
* نطاق [System::Xml](../../)
* مكتبة [Aspose.Slides](../../../)