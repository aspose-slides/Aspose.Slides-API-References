---
title: SelectSingleNode()
second_title: Aspose.Slides للغة C++ - مرجع API
description: يحدد أول XmlNode يتطابق مع تعبير XPath.
type: docs
weight: 352
url: /ar/system.xml/xmlnode/selectsinglenode/
---
## XmlNode::SelectSingleNode(const String\&) طريقة


يحدد أول [XmlNode](../) يتطابق مع تعبير [XPath](../../../system.xml.xpath/).

```cpp
SharedPtr<XmlNode> System::Xml::XmlNode::SelectSingleNode(const String &xpath)
```


### المعاملات

| معامل | نوع | وصف |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | تعبير [XPath](../../../system.xml.xpath/). |

### قيمة الإرجاع

أول [XmlNode](../) يتطابق مع استعلام [XPath](../../../system.xml.xpath/) أو **nullptr** إذا لم يتم العثور على عقدة مطابقة.

## XmlNode::SelectSingleNode(const String\&, const SharedPtr\<XmlNamespaceManager\>\&) طريقة


يحدد أول [XmlNode](../) يتطابق مع تعبير [XPath](../../../system.xml.xpath/). أي بادئات موجودة في تعبير [XPath](../../../system.xml.xpath/) يتم حلها باستخدام [XmlNamespaceManager](../../xmlnamespacemanager/) المقدم.

```cpp
SharedPtr<XmlNode> System::Xml::XmlNode::SelectSingleNode(const String &xpath, const SharedPtr<XmlNamespaceManager> &nsmgr)
```


### المعاملات

| معامل | نوع | وصف |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | تعبير [XPath](../../../system.xml.xpath/). |
| nsmgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | [XmlNamespaceManager](../../xmlnamespacemanager/) لاستخدامه في حل أسماء الفضاءات للمسافات في تعبير [XPath](../../../system.xml.xpath/). |

### قيمة الإرجاع

أول [XmlNode](../) يتطابق مع استعلام [XPath](../../../system.xml.xpath/) أو **nullptr** إذا لم يتم العثور على عقدة مطابقة.

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../)
* Class [String](../../../system/string/)
* Class [XmlNamespaceManager](../../xmlnamespacemanager/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)