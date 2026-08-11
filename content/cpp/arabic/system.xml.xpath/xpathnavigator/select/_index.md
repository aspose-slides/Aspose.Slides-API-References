---
title: Select()
second_title: مرجع API Aspose.Slides للـ C++
description: يحدد مجموعة من العقد باستخدام تعبير XPath المحدد.
type: docs
weight: 794
url: /ar/system.xml.xpath/xpathnavigator/select/
---
## XPathNavigator::Select(String) طريقة

يقوم بتحديد مجموعة من العقد باستخدام التعبير [XPath](../../) المحدد.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::Select(String xpath)
```

### المعاملات

| معامل | نوع | الوصف |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | [String](../../../system/string/) يمثل تعبير [XPath](../../). |

### قيمة الإرجاع

كائن [XPathNodeIterator](../../xpathnodeiterator/) يشير إلى مجموعة العقد المحددة.

## XPathNavigator::Select(String, SharedPtr\<IXmlNamespaceResolver\>) طريقة

يقوم بتحديد مجموعة من العقد باستخدام التعبير [XPath](../../) المحدد مع كائن [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) المحدد لحل بادئات المساحات الاسمية.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::Select(String xpath, SharedPtr<IXmlNamespaceResolver> resolver)
```

### المعاملات

| معامل | نوع | الوصف |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | [String](../../../system/string/) يمثل تعبير [XPath](../../). |
| resolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | كائن [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) المستخدم لحل بادئات المساحات الاسمية. |

### قيمة الإرجاع

كائن [XPathNodeIterator](../../xpathnodeiterator/) يشير إلى مجموعة العقد المحددة.

## XPathNavigator::Select(SharedPtr\<XPathExpression\>) طريقة

يقوم بتحديد مجموعة من العقد باستخدام [XPathExpression](../../xpathexpression/) المحدد.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::Select(SharedPtr<XPathExpression> expr)
```

### المعاملات

| معامل | نوع | الوصف |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | كائن [XPathExpression](../../xpathexpression/) يحتوي على استعلام [XPath](../../) المجمع. |

### قيمة الإرجاع

كائن [XPathNodeIterator](../../xpathnodeiterator/) يشير إلى مجموعة العقد المحددة.

## راجع أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [XPathNodeIterator](../../xpathnodeiterator/)
* فئة [String](../../../system/string/)
* فئة [XPathNavigator](../)
* فئة [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* فئة [XPathExpression](../../xpathexpression/)
* نطاق [System::Xml::XPath](../../)
* مكتبة [Aspose.Slides](../../../)