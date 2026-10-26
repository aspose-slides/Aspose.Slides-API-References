---
title: SelectAncestors()
second_title: مرجع Aspose.Slides للغة C++ API
description: يختار جميع عقد السلف للعنصر الحالي التي لها نوع XPathNodeType مطابق.
type: docs
weight: 846
url: /ar/system.xml.xpath/xpathnavigator/selectancestors/
---
## XPathNavigator::SelectAncestors(XPathNodeType, bool) طريقة

يختار جميع عقد السلف للعنصر الحالي التي لها نوع XPathNodeType مطابق.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectAncestors(XPathNodeType type, bool matchSelf)
```

### Arguments

| معامل | نوع | وصف |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | نوع XPathNodeType لعقد السلف. |
| matchSelf | **bool** | لتضمين عقدة السياق في الاختيار، **true**؛ وإلا **false**. |

### Return Value

كائن [XPathNodeIterator](../../xpathnodeiterator/) يحتوي على العقد المختارة. العقد المرتجعة بترتيب عكسي للمستند.

## XPathNavigator::SelectAncestors(String, String, bool) طريقة

يختار جميع عقد السلف للعنصر الحالي التي لها الاسم المحلي المحدد ومسار مساحة الاسم.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectAncestors(String name, String namespaceURI, bool matchSelf)
```

### Arguments

| معامل | نوع | وصف |
| --- | --- | --- |
| name | [String](../../../system/string/) | الاسم المحلي لعقد السلف. |
| namespaceURI | [String](../../../system/string/) | مسار مساحة الاسم لعقد السلف. |
| matchSelf | **bool** | لتضمين عقدة السياق في الاختيار، **true**؛ وإلا **false**. |

### Return Value

كائن [XPathNodeIterator](../../xpathnodeiterator/) يحتوي على العقد المختارة. العقد المرتجعة بترتيب عكسي للمستند.

## See Also

* Enum [XPathNodeType](../../xpathnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [XPathNodeIterator](../../xpathnodeiterator/)
* فئة [XPathNavigator](../)
* فئة [String](../../../system/string/)
* مساحة الاسم [System::Xml::XPath](../../)
* مكتبة [Aspose.Slides](../../../)