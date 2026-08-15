---
title: Select()
second_title: Aspose.Slides for C++ API 參考
description: 使用指定的 XPath 表達式選取節點集合。
type: docs
weight: 794
url: /zh-hant/system.xml.xpath/xpathnavigator/select/
---
## XPathNavigator::Select(String) 方法

使用指定的 [XPath](../../) 表達式選取節點集合。

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::Select(String xpath)
```

### Arguments

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | [String](../../../system/string/) 代表 [XPath](../../) 表示式。 |

### Return Value

指向所選節點集合的 [XPathNodeIterator](../../xpathnodeiterator/)。

## XPathNavigator::Select(String, SharedPtr\<IXmlNamespaceResolver\>) 方法

使用指定的 [XPath](../../) 表達式，並使用指定的 [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) 物件來解析名稱空間前置字元，以選取節點集合。

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::Select(String xpath, SharedPtr<IXmlNamespaceResolver> resolver)
```

### Arguments

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | [String](../../../system/string/) 代表 [XPath](../../) 表示式。 |
| resolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | 用於解析名稱空間前置字元的 [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) 物件。 |

### Return Value

指向所選節點集合的 [XPathNodeIterator](../../xpathnodeiterator/)。

## XPathNavigator::Select(SharedPtr\<XPathExpression\>) 方法

使用指定的 [XPathExpression](../../xpathexpression/) 來選取節點集合。

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::Select(SharedPtr<XPathExpression> expr)
```

### Arguments

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | 包含已編譯 [XPath](../../) 查詢的 [XPathExpression](../../xpathexpression/) 物件。 |

### Return Value

指向所選節點集合的 [XPathNodeIterator](../../xpathnodeiterator/)。

## 另見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [XPathNodeIterator](../../xpathnodeiterator/)
* 類別 [String](../../../system/string/)
* 類別 [XPathNavigator](../)
* 類別 [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* 類別 [XPathExpression](../../xpathexpression/)
* 命名空間 [System::Xml::XPath](../../)
* 函式庫 [Aspose.Slides](../../../)