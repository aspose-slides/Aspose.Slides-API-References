---
title: MoveToNext()
second_title: مرجع API Aspose.Slides للـ C++
description: عند تجاوزها في فئة مشتقة، تقوم بنقل XPathNavigator إلى عقدة الأخ المتاخرة التالية للعقدة الحالية.
type: docs
weight: 586
url: /ar/system.xml.xpath/xpathnavigator/movetonext/
---
## XPathNavigator::MoveToNext() طريقة

عند تجاوزها في فئة مشتقة، تقوم بنقل [XPathNavigator](../) إلى عقدة الأخ المتاخرة التالية للعقدة الحالية.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNext()=0
```

### قيمة الإرجاع

**true** إذا كان [XPathNavigator](../) ناجحًا في الانتقال إلى عقدة الأخ المتاخرة التالية؛ وإلا **false** إذا لم تعد هناك أخوة أخرى أو إذا كان [XPathNavigator](../) positioned على عقدة سمة. إذا **false**، يبقى موضع [XPathNavigator](../) دون تغيير.

## XPathNavigator::MoveToNext(String, String) طريقة

ينقل [XPathNavigator](../) إلى عقدة الأخ المتاخرة التالية التي لها الاسم المحلي ومسار مساحة الاسم المحددين.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNext(String localName, String namespaceURI)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| localName | [String](../../../system/string/) | الاسم المحلي لعقدة الأخ المتاخرة التالية التي سيتم الانتقال إليها. |
| namespaceURI | [String](../../../system/string/) | مسار مساحة الاسم لعقدة الأخ المتاخرة التالية التي سيتم الانتقال إليها. |

### قيمة الإرجاع

**true** إذا كان [XPathNavigator](../) ناجحًا في الانتقال إلى عقدة الأخ المتاخرة التالية؛ **false** إذا لم تعد هناك أخوة أخرى أو إذا كان [XPathNavigator](../) positioned على عقدة سمة. إذا **false**، يبقى موضع [XPathNavigator](../) دون تغيير.

## XPathNavigator::MoveToNext(XPathNodeType) طريقة

ينقل [XPathNavigator](../) إلى عقدة الأخ المتاخرة التالية للعقدة الحالية التي تطابق نوع XPathNodeType المحدد.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNext(XPathNodeType type)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | نوع XPathNodeType لعقدة الأخ التي سيتم الانتقال إليها. |

### قيمة الإرجاع

**true** إذا كان [XPathNavigator](../) ناجحًا في الانتقال إلى عقدة الأخ المتاخرة التالية؛ وإلا **false** إذا لم تعد هناك أخوة أخرى أو إذا كان [XPathNavigator](../) positioned على عقدة سمة. إذا **false**، يبقى موضع [XPathNavigator](../) دون تغيير.

## انظر أيضاً

* Enum [XPathNodeType](../../xpathnodetype/)
* فئة [XPathNavigator](../)
* فئة [String](../../../system/string/)
* نطاق [System::Xml::XPath](../../)
* مكتبة [Aspose.Slides](../../../)