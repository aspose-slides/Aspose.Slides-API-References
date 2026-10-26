---
title: InsertBefore()
second_title: مرجع API Aspose.Slides لـ C++
description: يعيد كائن XmlWriter يُستخدم لإنشاء عقدة شقيقة جديدة قبل العقدة المحددة حاليًا.
type: docs
weight: 911
url: /ar/system.xml.xpath/xpathnavigator/insertbefore/
---
## XPathNavigator::InsertBefore() طريقة


يرجع كائن [XmlWriter](../../../system.xml/xmlwriter/) يُستخدم لإنشاء عقدة شقيقة جديدة قبل العقدة المحددة حاليًا.

```cpp
virtual SharedPtr<XmlWriter> System::Xml::XPath::XPathNavigator::InsertBefore()
```


### قيمة الإرجاع

كائن [XmlWriter](../../../system.xml/xmlwriter/) يُستخدم لإنشاء عقدة شقيقة جديدة قبل العقدة المحددة حاليًا.

## XPathNavigator::InsertBefore(String) طريقة


يُنشئ عقدة شقيقة جديدة قبل العقدة المحددة حاليًا باستخدام سلسلة XML المحددة.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertBefore(String newSibling)
```


### المعطيات

| Parameter | Type | Description |
| --- | --- | --- |
| newSibling | [String](../../../system/string/) | سلسلة بيانات XML للعقدة الشقيقة الجديدة. |

## XPathNavigator::InsertBefore(SharedPtr\<XmlReader\>) طريقة


يُنشئ عقدة شقيقة جديدة قبل العقدة المحددة حاليًا باستخدام محتويات XML للكائن [XmlReader](../../../system.xml/xmlreader/) المحدد.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertBefore(SharedPtr<XmlReader> newSibling)
```


### المعطيات

| Parameter | Type | Description |
| --- | --- | --- |
| newSibling | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | كائن [XmlReader](../../../system.xml/xmlreader/) موضع على بيانات XML للعقدة الشقيقة الجديدة. |

## XPathNavigator::InsertBefore(SharedPtr\<XPathNavigator\>) طريقة


يُنشئ عقدة شقيقة جديدة قبل العقدة المحددة حاليًا باستخدام العقد الموجودة في [XPathNavigator](../) المحدد.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertBefore(SharedPtr<XPathNavigator> newSibling)
```


### المعطيات

| Parameter | Type | Description |
| --- | --- | --- |
| newSibling | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | كائن [XPathNavigator](../) موضع على العقدة التي تُضاف كعقدة شقيقة جديدة. |

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlWriter](../../../system.xml/xmlwriter/)
* Class [XPathNavigator](../)
* Class [String](../../../system/string/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)