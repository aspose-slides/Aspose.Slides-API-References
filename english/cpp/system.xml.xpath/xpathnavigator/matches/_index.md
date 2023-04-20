---
title: Matches()
second_title: Aspose.Slides for C++ API Reference
description: Determines whether the current node matches the specified XPathExpression.
type: docs
weight: 820
url: /cpp/system.xml.xpath/xpathnavigator/matches/
---
## XPathNavigator::Matches(SharedPtr\<XPathExpression\>) method


Determines whether the current node matches the specified [XPathExpression](../../xpathexpression/).

```cpp
virtual bool System::Xml::XPath::XPathNavigator::Matches(SharedPtr<XPathExpression> expr)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | An [XPathExpression](../../xpathexpression/) object containing the compiled [XPath](../../) expression. |

### Return Value

**true** if the current node matches the [XPathExpression](../../xpathexpression/); otherwise, **false**.

## XPathNavigator::Matches(String) method


Determines whether the current node matches the specified [XPath](../../) expression.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::Matches(String xpath)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | The [XPath](../../) expression. |

### Return Value

**true** if the current node matches the specified [XPath](../../) expression; otherwise, **false**.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathExpression](../../xpathexpression/)
* Class [XPathNavigator](../)
* Class [String](../../../system/string/)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)