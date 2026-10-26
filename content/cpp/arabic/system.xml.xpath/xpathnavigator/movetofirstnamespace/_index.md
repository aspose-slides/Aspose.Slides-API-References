---
title: MoveToFirstNamespace()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: عند تجاوزها في فئة مشتقة، تنقل XPathNavigator إلى أول عقدة مساحة اسم تتطابق مع XPathNamespaceScope المحدد.
type: docs
weight: 560
url: /ar/system.xml.xpath/xpathnavigator/movetofirstnamespace/
---
## XPathNavigator::MoveToFirstNamespace(XPathNamespaceScope) الطريقة

When overridden in a derived class, moves the [XPathNavigator](../) to the first namespace node that matches the XPathNamespaceScope specified.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFirstNamespace(XPathNamespaceScope namespaceScope)=0
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| namespaceScope | [XPathNamespaceScope](../../xpathnamespacescope/) | قيمة XPathNamespaceScope تصف نطاق مساحة الاسم. |

### قيمة الإرجاع

**true** إذا كان [XPathNavigator](../) ناجحًا في الانتقال إلى عقدة مساحة الاسم الأولى؛ وإلا، **false**. إذا كان **false**، فإن موضع [XPathNavigator](../) يبقى دون تغيير.

## XPathNavigator::MoveToFirstNamespace() الطريقة

ينقل [XPathNavigator](../) إلى عقدة مساحة الاسم الأولى للعقدة الحالية.

```cpp
bool System::Xml::XPath::XPathNavigator::MoveToFirstNamespace()
```

### قيمة الإرجاع

**true** إذا كان [XPathNavigator](../) ناجحًا في الانتقال إلى عقدة مساحة الاسم الأولى؛ وإلا، **false**. إذا كان **false**، فإن موضع [XPathNavigator](../) يبقى دون تغيير.

## راجع أيضًا

* تعداد [XPathNamespaceScope](../../xpathnamespacescope/)
* فئة [XPathNavigator](../)
* نطاق [System::Xml::XPath](../../)
* مكتبة [Aspose.Slides](../../../)