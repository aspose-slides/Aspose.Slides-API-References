---
title: MoveToChild()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: ينقل الـ XPathNavigator إلى العقدة الفرعية التي لها الاسم المحلي وURI مساحة الاسم المحددين.
type: docs
weight: 690
url: /ar/system.xml.xpath/xpathnavigator/movetochild/
---
## XPathNavigator::MoveToChild(String, String) طريقة

ينقل الـ [XPathNavigator](../) إلى العقدة الفرعية التي لها الاسم المحلي وURI مساحة الاسم المحددين.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToChild(String localName, String namespaceURI)
```

### المعاملات

| معامل | نوع | وصف |
| --- | --- | --- |
| localName | [String](../../../system/string/) | الاسم المحلي للعقدة الفرعية التي سيتم الانتقال إليها. |
| namespaceURI | [String](../../../system/string/) | URI مساحة الاسم للعقدة الفرعية التي سيتم الانتقال إليها. |

### قيمة الإرجاع

**true** إذا كان [XPathNavigator](../) ناجحًا في الانتقال إلى العقدة الفرعية؛ وإلا فإن **false**. إذا كان **false**، فإن موضع [XPathNavigator](../) يظل دون تغيير.

## XPathNavigator::MoveToChild(XPathNodeType) طريقة

ينقل الـ [XPathNavigator](../) إلى العقدة الفرعية من نوع XPathNodeType المحدد.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToChild(XPathNodeType type)
```

### المعاملات

| معامل | نوع | وصف |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | نوع XPathNodeType للعقدة الفرعية التي سيتم الانتقال إليها. |

### قيمة الإرجاع

**true** إذا كان [XPathNavigator](../) ناجحًا في الانتقال إلى العقدة الفرعية؛ وإلا فإن **false**. إذا كان **false**، فإن موضع [XPathNavigator](../) يظل دون تغيير.

## انظر أيضًا

* تعدد [XPathNodeType](../../xpathnodetype/)
* فئة [String](../../../system/string/)
* فئة [XPathNavigator](../)
* نطاق [System::Xml::XPath](../../)
* مكتبة [Aspose.Slides](../../../)