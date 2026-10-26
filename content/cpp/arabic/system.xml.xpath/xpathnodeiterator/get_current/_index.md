---
title: get_Current()
second_title: مرجع API Aspose.Slides للغة C++
description: عند تجاوزها في فئة مشتقة، تحصل على كائن XPathNavigator لهذا XPathNodeIterator، الموضع على عقدة السياق الحالية.
type: docs
weight: 1
url: /ar/system.xml.xpath/xpathnodeiterator/get_current/
---
## XPathNodeIterator::get_Current() طريقة


عند تجاوزها في فئة مشتقة، تحصل على كائن [XPathNavigator](../../xpathnavigator/) لهذا [XPathNodeIterator](../)، موضعه على عقدة السياق الحالية.

```cpp
virtual const SharedPtr<XPathNavigator> & System::Xml::XPath::XPathNodeIterator::get_Current()=0
```


### قيمة الإرجاع

كائن [XPathNavigator](../../xpathnavigator/) موضعه على عقدة السياق التي تم منها اختيار مجموعة العقد. يجب استدعاء طريقة [XPathNodeIterator::MoveNext](../movenext/) لتحريك [XPathNodeIterator](../) إلى أول عقدة في المجموعة المحددة.

## انظر أيضاً

* تعريف النوع [SharedPtr](../../../system/sharedptr/)
* فئة [XPathNavigator](../../xpathnavigator/)
* فئة [XPathNodeIterator](../)
* مساحة الاسم [System::Xml::XPath](../../)
* مكتبة [Aspose.Slides](../../../)