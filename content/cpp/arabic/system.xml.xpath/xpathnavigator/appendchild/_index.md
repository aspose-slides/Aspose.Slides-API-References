---
title: AppendChild()
second_title: مرجع API Aspose.Slides للغة C++
description: يعيد كائن XmlWriter يُستخدم لإنشاء عقد طفل جديدة واحدة أو أكثر في نهاية قائمة العقود الفرعية للعقدة الحالية.
type: docs
weight: 885
url: /ar/system.xml.xpath/xpathnavigator/appendchild/
---
## XPathNavigator::AppendChild() طريقة

يعيد كائن [XmlWriter](../../../system.xml/xmlwriter/) يُستخدم لإنشاء عقد طفل جديدة واحدة أو أكثر في نهاية قائمة العقود الفرعية للعقدة الحالية.

```cpp
virtual SharedPtr<XmlWriter> System::Xml::XPath::XPathNavigator::AppendChild()
```

### قيمة الإرجاع

كائن [XmlWriter](../../../system.xml/xmlwriter/) يُستخدم لإنشاء عقد طفل جديدة في نهاية قائمة العقود الفرعية للعقدة الحالية.

## XPathNavigator::AppendChild(String) طريقة

يُنشئ عقدة طفل جديدة في نهاية قائمة العقود الفرعية للعقدة الحالية باستخدام سلسلة بيانات XML المحددة.

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChild(String newChild)
```

### معلمات

| معامل | نوع | وصف |
| --- | --- | --- |
| newChild | [String](../../../system/string/) | سلسلة بيانات XML للعقدة الطفل الجديدة. |

## XPathNavigator::AppendChild(SharedPtr\<XmlReader\>) طريقة

يُنشئ عقدة طفل جديدة في نهاية قائمة العقود الفرعية للعقدة الحالية باستخدام محتويات XML للكائن [XmlReader](../../../system.xml/xmlreader/) المحدد.

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChild(SharedPtr<XmlReader> newChild)
```

### معلمات

| معامل | نوع | وصف |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | كائن [XmlReader](../../../system.xml/xmlreader/) موضع على بيانات XML للعقدة الطفل الجديدة. |

## XPathNavigator::AppendChild(SharedPtr\<XPathNavigator\>) طريقة

يُنشئ عقدة طفل جديدة في نهاية قائمة العقود الفرعية للعقدة الحالية باستخدام العقد الموجودة في [XPathNavigator](../) المحدد.

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChild(SharedPtr<XPathNavigator> newChild)
```

### معلمات

| معامل | نوع | وصف |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | كائن [XPathNavigator](../) موضع على العقدة لإضافتها كعقدة طفل جديدة. |

## انظر أيضاً

* Typedef [SharedPtr](../../../system/sharedptr/)
* الفئة [XmlWriter](../../../system.xml/xmlwriter/)
* الفئة [XPathNavigator](../)
* الفئة [String](../../../system/string/)
* الفئة [XmlReader](../../../system.xml/xmlreader/)
* نطاق [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)