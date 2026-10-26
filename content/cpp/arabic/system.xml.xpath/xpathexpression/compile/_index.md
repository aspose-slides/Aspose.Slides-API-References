---
title: Compile()
second_title: مرجع API Aspose.Slides للغة C++
description: يقوم بتجميع تعبير XPath المحدد ويعيد كائن XPathExpression يمثل تعبير XPath.
type: docs
weight: 66
url: /ar/system.xml.xpath/xpathexpression/compile/
---
## XPathExpression::Compile(const String\&) طريقة

يقوم بتجميع التعبير [XPath](../../) المحدد ويعيد كائن [XPathExpression](../) يمثل التعبير [XPath](../../).

```cpp
static SharedPtr<XPathExpression> System::Xml::XPath::XPathExpression::Compile(const String &xpath)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | تعبير [XPath](../../). |

### قيمة الإرجاع

كائن [XPathExpression](../).

## XPathExpression::Compile(const String\&, const SharedPtr\<IXmlNamespaceResolver\>\&) طريقة

يقوم بتجميع التعبير [XPath](../../) المحدد، مع كائن [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) المحدد لحل المساحات الاسمية، ويعيد كائن [XPathExpression](../) يمثل التعبير [XPath](../../).

```cpp
static SharedPtr<XPathExpression> System::Xml::XPath::XPathExpression::Compile(const String &xpath, const SharedPtr<IXmlNamespaceResolver> &nsResolver)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | تعبير [XPath](../../). |
| nsResolver | const [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\>\& | كائن يطبق واجهة [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) لحل المساحات الاسمية. |

### قيمة الإرجاع

كائن [XPathExpression](../).

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [XPathExpression](../)
* فئة [String](../../../system/string/)
* فئة [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* نطاق [System::Xml::XPath](../../)
* مكتبة [Aspose.Slides](../../../)