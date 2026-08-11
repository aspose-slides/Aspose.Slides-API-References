---
title: MoveToNextNamespace()
second_title: Aspose.Slides لـ C++ مرجع API
description: عند تجاوزها في فئة مشتقة، تنقل XPathNavigator إلى العقدة التالية لمساحة الاسم التي تطابق نطاق XPathNamespaceScope المحدد.
type: docs
weight: 573
url: /ar/system.xml.xpath/xpathnavigator/movetonextnamespace/
---
## XPathNavigator::MoveToNextNamespace(XPathNamespaceScope) طريقة

When overridden in a derived class, moves the [XPathNavigator](../) to the next namespace node matching the XPathNamespaceScope specified.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNextNamespace(XPathNamespaceScope namespaceScope)=0
```

### وسائط

| معامل | نوع | الوصف |
| --- | --- | --- |
| namespaceScope | [XPathNamespaceScope](../../xpathnamespacescope/) | قيمة XPathNamespaceScope تصف نطاق مساحة الاسم. |

### قيمة الإرجاع

**true** إذا كان [XPathNavigator](../) ناجحًا في الانتقال إلى عقدة المساحة الاسمية التالية؛ وإلا، **false**. إذا كان **false**، فإن موضع [XPathNavigator](../) يبقى دون تغيير.

## XPathNavigator::MoveToNextNamespace() طريقة

Moves the [XPathNavigator](../) to the next namespace node.

```cpp
bool System::Xml::XPath::XPathNavigator::MoveToNextNamespace()
```

### قيمة الإرجاع

**true** إذا كان [XPathNavigator](../) ناجحًا في الانتقال إلى عقدة المساحة الاسمية التالية؛ وإلا، **false**. إذا كان **false**، فإن موضع [XPathNavigator](../) يبقى دون تغيير.

## انظر أيضًا

* تعداد [XPathNamespaceScope](../../xpathnamespacescope/)
* فئة [XPathNavigator](../)
* نطاق [System::Xml::XPath](../../)
* مكتبة [Aspose.Slides](../../../)