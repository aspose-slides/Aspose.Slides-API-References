---
title: Matches()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يحدد ما إذا كانت العقدة الحالية تطابق XPathExpression المحدد.
type: docs
weight: 820
url: /ar/system.xml.xpath/xpathnavigator/matches/
---
## XPathNavigator::Matches(SharedPtr\<XPathExpression\>) طريقة

يحدد ما إذا كانت العقدة الحالية تطابق [XPathExpression](../../xpathexpression/) المحدد.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::Matches(SharedPtr<XPathExpression> expr)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | كائن [XPathExpression](../../xpathexpression/) يحتوي على تعبير [XPath](../../) المترجم. |

### قيمة الإرجاع

**true** إذا كانت العقدة الحالية تطابق [XPathExpression](../../xpathexpression/)؛ وإلا، **false**.

## XPathNavigator::Matches(String) طريقة

يحدد ما إذا كانت العقدة الحالية تطابق تعبير [XPath](../../) المحدد.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::Matches(String xpath)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | تعبير [XPath](../../). |

### قيمة الإرجاع

**true** إذا كانت العقدة الحالية تطابق تعبير [XPath](../../) المحدد؛ وإلا، **false**.

## انظر أيضًا

* تعريف النوع [SharedPtr](../../../system/sharedptr/)
* فئة [XPathExpression](../../xpathexpression/)
* فئة [XPathNavigator](../)
* فئة [String](../../../system/string/)
* مساحة الاسم [System::Xml::XPath](../../)
* مكتبة [Aspose.Slides](../../../)