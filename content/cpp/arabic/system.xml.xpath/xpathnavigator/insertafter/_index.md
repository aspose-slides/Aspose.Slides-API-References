---
title: InsertAfter()
second_title: مرجع واجهة برمجة التطبيقات Aspose.Slides للغة C++
description: يعيد كائن XmlWriter يُستخدم لإنشاء عقدة شقيقة جديدة بعد العقدة المحددة حاليًا.
type: docs
weight: 898
url: /ar/system.xml.xpath/xpathnavigator/insertafter/
---
## XPathNavigator::InsertAfter() method

يعيد كائن [XmlWriter](../../../system.xml/xmlwriter/) يُستخدم لإنشاء عقدة شقيقة جديدة بعد العقدة المحددة حاليًا.

```cpp
virtual SharedPtr<XmlWriter> System::Xml::XPath::XPathNavigator::InsertAfter()
```

### قيمة الإرجاع

كائن [XmlWriter](../../../system.xml/xmlwriter/) يُستخدم لإنشاء عقدة شقيقة جديدة بعد العقدة المحددة حاليًا.

## XPathNavigator::InsertAfter(String) method

ينشئ عقدة شقيقة جديدة بعد العقدة المحددة حاليًا باستخدام سلسلة XML المحددة.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertAfter(String newSibling)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| newSibling | [String](../../../system/string/) | سلسلة بيانات XML للعقدة الشقيقة الجديدة. |

## XPathNavigator::InsertAfter(SharedPtr\<XmlReader\>) method

ينشئ عقدة شقيقة جديدة بعد العقدة المحددة حاليًا باستخدام محتويات XML للكائن [XmlReader](../../../system.xml/xmlreader/) المحدد.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertAfter(SharedPtr<XmlReader> newSibling)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| newSibling | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | كائن [XmlReader](../../../system.xml/xmlreader/) موضع على بيانات XML للعقدة الشقيقة الجديدة. |

## XPathNavigator::InsertAfter(SharedPtr\<XPathNavigator\>) method

ينشئ عقدة شقيقة جديدة بعد العقدة المحددة حاليًا باستخدام العقد في الكائن [XPathNavigator](../) المحدد.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertAfter(SharedPtr<XPathNavigator> newSibling)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| newSibling | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | كائن [XPathNavigator](../) موضع على العقدة لإضافتها كعقدة شقيقة جديدة. |

## انظر أيضًا

* تعريف النوع [SharedPtr](../../../system/sharedptr/)
* فئة [XmlWriter](../../../system.xml/xmlwriter/)
* فئة [XPathNavigator](../)
* فئة [String](../../../system/string/)
* فئة [XmlReader](../../../system.xml/xmlreader/)
* مساحة الاسم [System::Xml::XPath](../../)
* مكتبة [Aspose.Slides](../../../)