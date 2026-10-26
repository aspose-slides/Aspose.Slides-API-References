---
title: SelectSingleNode()
second_title: مرجع API Aspose.Slides للـ C++
description: يختار عقدة واحدة في XPathNavigator باستخدام استعلام XPath المحدد.
type: docs
weight: 781
url: /ar/system.xml.xpath/xpathnavigator/selectsinglenode/
---
## XPathNavigator::SelectSingleNode(String) طريقة

يختار عقدة واحدة في [XPathNavigator](../) باستخدام الاستعلام [XPath](../../) المحدد.

```cpp
virtual SharedPtr<XPathNavigator> System::Xml::XPath::XPathNavigator::SelectSingleNode(String xpath)
```

### المعاملات

| معامل | نوع | وصف |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | كائن [String](../../../system/string/) يمثل تعبير [XPath](../../). |

### قيمة الإرجاع

كائن [XPathNavigator](../) يحتوي على أول عقدة مطابقة للاستعلام [XPath](../../) المحدد؛ وإلا **nullptr** إذا لم تكن هناك نتائج للاستعلام.

## XPathNavigator::SelectSingleNode(String, SharedPtr\<IXmlNamespaceResolver\>) طريقة

يختار عقدة واحدة في كائن [XPathNavigator](../) باستخدام الاستعلام [XPath](../../) المحدد مع كائن [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) المحدد لحل بادئات النطاق.

```cpp
virtual SharedPtr<XPathNavigator> System::Xml::XPath::XPathNavigator::SelectSingleNode(String xpath, SharedPtr<IXmlNamespaceResolver> resolver)
```

### المعاملات

| معامل | نوع | وصف |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | كائن [String](../../../system/string/) يمثل تعبير [XPath](../../). |
| resolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | الكائن [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) المستخدم لحل بادئات النطاق في استعلام [XPath](../../). |

### قيمة الإرجاع

كائن [XPathNavigator](../) يحتوي على أول عقدة مطابقة للاستعلام [XPath](../../) المحدد؛ وإلا **nullptr** إذا لم تكن هناك نتائج للاستعلام.

## XPathNavigator::SelectSingleNode(SharedPtr\<XPathExpression\>) طريقة

يختار عقدة واحدة في [XPathNavigator](../) باستخدام الكائن [XPathExpression](../../xpathexpression/) المحدد.

```cpp
virtual SharedPtr<XPathNavigator> System::Xml::XPath::XPathNavigator::SelectSingleNode(SharedPtr<XPathExpression> expression)
```

### المعاملات

| معامل | نوع | وصف |
| --- | --- | --- |
| expression | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | كائن [XPathExpression](../../xpathexpression/) يحتوي على استعلام [XPath](../../) المُجمّع. |

### قيمة الإرجاع

كائن [XPathNavigator](../) يحتوي على أول عقدة مطابقة للاستعلام [XPath](../../) المحدد؛ وإلا **nullptr** إذا لم تكن هناك نتائج للاستعلام.

## أنظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [XPathNavigator](../)
* فئة [String](../../../system/string/)
* فئة [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* فئة [XPathExpression](../../xpathexpression/)
* نطاق [System::Xml::XPath](../../)
* مكتبة [Aspose.Slides](../../../)