---
title: MoveTo()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: عند تجاوزها في فئة مشتقة، تنقل XPathNavigator إلى نفس الموضع كما هو محدد في XPathNavigator المحدد.
type: docs
weight: 664
url: /ar/system.xml.xpath/xpathnavigator/moveto/
---
## XPathNavigator::MoveTo(SharedPtr\<XPathNavigator\>) طريقة

When overridden in a derived class, moves the [XPathNavigator](../) to the same position as the specified [XPathNavigator](../).

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveTo(SharedPtr<XPathNavigator> other)=0
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| other | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | الـ [XPathNavigator](../) الموجود على العقدة التي تريد الانتقال إليها. |

### قيمة الإرجاع

**true** إذا كان [XPathNavigator](../) ناجحًا في الانتقال إلى نفس الموضع كما هو محدد [XPathNavigator](../)؛ وإلا، **false**. إذا **false**، يبقى موضع [XPathNavigator](../) دون تغيير.

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [XPathNavigator](../)
* نطاق الاسم [System::Xml::XPath](../../)
* مكتبة [Aspose.Slides](../../../)