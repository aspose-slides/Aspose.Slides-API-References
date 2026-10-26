---
title: SelectChildren()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يحدد جميع العقد الفرعية للعقدة الحالية التي لها نوع XPathNodeType المطابق.
type: docs
weight: 833
url: /ar/system.xml.xpath/xpathnavigator/selectchildren/
---
## XPathNavigator::SelectChildren(XPathNodeType) طريقة

يحدد جميع العقد الفرعية للعقدة الحالية التي لها نوع XPathNodeType المتطابق.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectChildren(XPathNodeType type)
```

### المعلمات

| معامل | نوع | الوصف |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | نوع XPathNodeType للعقد الفرعية. |

### قيمة الإرجاع

[XPathNodeIterator](../../xpathnodeiterator/) يحتوي على العقد المحددة.

## XPathNavigator::SelectChildren(String, String) طريقة

يحدد جميع العقد الفرعية للعقدة الحالية التي لها الاسم المحلي وURI مساحة الاسم المحدد.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectChildren(String name, String namespaceURI)
```

### المعلمات

| معامل | نوع | الوصف |
| --- | --- | --- |
| name | [String](../../../system/string/) | الاسم المحلي للعقد الفرعية. |
| namespaceURI | [String](../../../system/string/) | URI مساحة الاسم للعقد الفرعية. |

### قيمة الإرجاع

[XPathNodeIterator](../../xpathnodeiterator/) يحتوي على العقد المحددة.

## انظر أيضًا

* عدد [XPathNodeType](../../xpathnodetype/)
* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [XPathNodeIterator](../../xpathnodeiterator/)
* فئة [XPathNavigator](../)
* فئة [String](../../../system/string/)
* مساحة الاسم [System::Xml::XPath](../../)
* مكتبة [Aspose.Slides](../../../)