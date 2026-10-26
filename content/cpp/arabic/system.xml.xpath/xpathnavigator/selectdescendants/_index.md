---
title: SelectDescendants()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يختار جميع العقد التابعة للعقدة الحالية التي لها نوع XPathNodeType مطابق.
type: docs
weight: 859
url: /ar/system.xml.xpath/xpathnavigator/selectdescendants/
---
## XPathNavigator::SelectDescendants(XPathNodeType, bool) طريقة


يختار جميع العقد التابعة للعقدة الحالية التي لها نوع XPathNodeType مطابق.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectDescendants(XPathNodeType type, bool matchSelf)
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | نوع XPathNodeType للعقد التابعة. |
| matchSelf | **bool** | **true** لتضمين عقدة السياق في الاختيار؛ وإلا **false**. |

### قيمة الإرجاع

[XPathNodeIterator](../../xpathnodeiterator/) يحتوي على العقد المحددة.

## XPathNavigator::SelectDescendants(String, String, bool) طريقة


يختار جميع العقد التابعة للعقدة الحالية بالاسم المحلي وURI مساحة الأسماء المحددين.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectDescendants(String name, String namespaceURI, bool matchSelf)
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | [String](../../../system/string/) | الاسم المحلي للعقد التابعة. |
| namespaceURI | [String](../../../system/string/) | URI مساحة الأسماء للعقد التابعة. |
| matchSelf | **bool** | **true** لتضمين عقدة السياق في الاختيار؛ وإلا **false**. |

### قيمة الإرجاع

[XPathNodeIterator](../../xpathnodeiterator/) يحتوي على العقد المحددة.

## انظر أيضًا

* عدد [XPathNodeType](../../xpathnodetype/)
* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* صنف [XPathNodeIterator](../../xpathnodeiterator/)
* صنف [XPathNavigator](../)
* صنف [String](../../../system/string/)
* نطاق [System::Xml::XPath](../../)
* مكتبة [Aspose.Slides](../../../)