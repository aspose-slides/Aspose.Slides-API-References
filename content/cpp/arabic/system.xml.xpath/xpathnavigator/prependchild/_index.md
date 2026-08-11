---
title: PrependChild()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يعيد كائن XmlWriter يُستخدم لإنشاء عقدة فرعية جديدة في بداية قائمة العقد الفرعية للعقدة الحالية.
type: docs
weight: 872
url: /ar/system.xml.xpath/xpathnavigator/prependchild/
---
## XPathNavigator::PrependChild() طريقة

يعيد كائن [XmlWriter](../../../system.xml/xmlwriter/) يُستخدم لإنشاء عقدة فرعية جديدة في بداية قائمة العقد الفرعية للعقدة الحالية.

```cpp
virtual SharedPtr<XmlWriter> System::Xml::XPath::XPathNavigator::PrependChild()
```

### قيمة الإرجاع

كائن [XmlWriter](../../../system.xml/xmlwriter/) يُستخدم لإنشاء عقدة فرعية جديدة في بداية قائمة العقد الفرعية للعقدة الحالية.

## XPathNavigator::PrependChild(String) طريقة

ينشئ عقدة فرعية جديدة في بداية قائمة العقد الفرعية للعقدة الحالية باستخدام سلسلة XML المحددة.

```cpp
virtual void System::Xml::XPath::XPathNavigator::PrependChild(String newChild)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| newChild | [String](../../../system/string/) | سلسلة بيانات XML للعقدة الفرعية الجديدة. |

## XPathNavigator::PrependChild(SharedPtr\<XmlReader\>) طريقة

ينشئ عقدة فرعية جديدة في بداية قائمة العقد الفرعية للعقدة الحالية باستخدام محتويات XML لكائن [XmlReader](../../../system.xml/xmlreader/) المحدد.

```cpp
virtual void System::Xml::XPath::XPathNavigator::PrependChild(SharedPtr<XmlReader> newChild)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | كائن [XmlReader](../../../system.xml/xmlreader/) يتموضع على بيانات XML للعقدة الفرعية الجديدة. |

## XPathNavigator::PrependChild(SharedPtr\<XPathNavigator\>) طريقة

ينشئ عقدة فرعية جديدة في بداية قائمة العقد الفرعية للعقدة الحالية باستخدام العقد الموجودة في كائن [XPathNavigator](../) المحدد.

```cpp
virtual void System::Xml::XPath::XPathNavigator::PrependChild(SharedPtr<XPathNavigator> newChild)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | كائن [XPathNavigator](../) يتموضع على العقدة التي ستُضاف كعقدة فرعية جديدة. |

## انظر أيضا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* الصنف [XmlWriter](../../../system.xml/xmlwriter/)
* الصنف [XPathNavigator](../)
* الصنف [String](../../../system/string/)
* الصنف [XmlReader](../../../system.xml/xmlreader/)
* النطاق [System::Xml::XPath](../../)
* المكتبة [Aspose.Slides](../../../)