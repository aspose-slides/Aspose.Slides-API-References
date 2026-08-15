---
title: SelectSingleNode()
second_title: Aspose.Slides for C++ API 參考
description: 使用指定的 XPath 查詢，在 XPathNavigator 中選取單一節點。
type: docs
weight: 781
url: /zh-hant/system.xml.xpath/xpathnavigator/selectsinglenode/
---
## XPathNavigator::SelectSingleNode(String) 方法

使用指定的 [XPath](../../) 查詢，在 [XPathNavigator](../) 中選取單一節點。

```cpp
virtual SharedPtr<XPathNavigator> System::Xml::XPath::XPathNavigator::SelectSingleNode(String xpath)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | 代表 [XPath](../../) 表達式的 [String](../../../system/string/)。 |

### Return Value

若指定的 [XPath](../../) 查詢有符合的節點，返回包含第一個匹配節點的 [XPathNavigator](../) 物件；若無查詢結果，則返回 **nullptr**。

## XPathNavigator::SelectSingleNode(String, SharedPtr\<IXmlNamespaceResolver\>) 方法

使用指定的 [XPath](../../) 查詢，並使用指定的 [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) 物件來解析命名空間前綴，在 [XPathNavigator](../) 物件中選取單一節點。

```cpp
virtual SharedPtr<XPathNavigator> System::Xml::XPath::XPathNavigator::SelectSingleNode(String xpath, SharedPtr<IXmlNamespaceResolver> resolver)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | 代表 [XPath](../../) 表達式的 [String](../../../system/string/)。 |
| resolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | [XPath](../../) 查詢中用於解析命名空間前綴的 [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) 物件。 |

### Return Value

若指定的 [XPath](../../) 查詢有符合的節點，返回包含第一個匹配節點的 [XPathNavigator](../) 物件；若無查詢結果，則返回 **nullptr**。

## XPathNavigator::SelectSingleNode(SharedPtr\<XPathExpression\>) 方法

使用指定的 [XPathExpression](../../xpathexpression/) 物件，在 [XPathNavigator](../) 中選取單一節點。

```cpp
virtual SharedPtr<XPathNavigator> System::Xml::XPath::XPathNavigator::SelectSingleNode(SharedPtr<XPathExpression> expression)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| expression | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | 包含已編譯 [XPath](../../) 查詢的 [XPathExpression](../../xpathexpression/) 物件。 |

### Return Value

若指定的 [XPath](../../) 查詢有符合的節點，返回包含第一個匹配節點的 [XPathNavigator](../) 物件；若無查詢結果，則返回 **nullptr**。

## 另見

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNavigator](../)
* Class [String](../../../system/string/)
* Class [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Class [XPathExpression](../../xpathexpression/)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)