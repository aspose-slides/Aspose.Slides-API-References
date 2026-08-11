---
title: MoveToFirst()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: ينقل XPathNavigator إلى أول عقدة شقيقة للعقدة الحالية.
type: docs
weight: 612
url: /ar/system.xml.xpath/xpathnavigator/movetofirst/
---
## XPathNavigator::MoveToFirst() method


ينقل [XPathNavigator](../) إلى أول عقدة شقيقة للعقدة الحالية.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFirst()
```


### قيمة الإرجاع

**true** إذا كان [XPathNavigator](../) ناجحًا في الانتقال إلى أول عقدة شقيقة للعقدة الحالية؛ **false** إذا لم يكن هناك أول شقيق، أو إذا كان [XPathNavigator](../) موجودًا حاليًا على عقدة سمة. إذا كان [XPathNavigator](../) موجودًا بالفعل على أول شقيق، فإن [XPathNavigator](../) سيعيد **true** ولن يغيّر موقعه. إذا أعاد [XPathNavigator::MoveToFirst](./) **false** لأنه لا يوجد أول شقيق، أو إذا كان [XPathNavigator](../) موجودًا حاليًا على سمة، فإن موضع [XPathNavigator](../) يبقى دون تغيير.

## انظر أيضًا

* الفئة [XPathNavigator](../)
* النطاق [System::Xml::XPath](../../)
* المكتبة [Aspose.Slides](../../../)