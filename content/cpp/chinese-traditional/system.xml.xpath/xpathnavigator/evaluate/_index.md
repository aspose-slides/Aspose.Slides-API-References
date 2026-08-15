---
title: Evaluate()
second_title: Aspose.Slides for C++ API 參考文件
description: 評估指定的 XPath 表達式，並返回具類型的結果。
type: docs
weight: 807
url: /zh-hant/system.xml.xpath/xpathnavigator/evaluate/
---
## XPathNavigator::Evaluate(String) 方法


評估指定的 [XPath](../../) 表達式，並返回具類型的結果。

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(String xpath)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | 表示可評估的 [XPath](../../) 表達式的字串。 |

### 返回值

表達式的結果 ([Boolean](../../../system/boolean/)、數字、字串或節點集)。這分別對應到 [Boolean](../../../system/boolean/)、[Double](../../../system/double/)、[String](../../../system/string/) 或 [XPathNodeIterator](../../xpathnodeiterator/) 物件。

## XPathNavigator::Evaluate(String, SharedPtr\<IXmlNamespaceResolver\>) 方法


評估指定的 [XPath](../../) 表達式，並返回具類型的結果，使用指定的 [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) 物件解析 [XPath](../../) 表達式中的命名空間前綴。

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(String xpath, SharedPtr<IXmlNamespaceResolver> resolver)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | 表示可評估的 [XPath](../../) 表達式的字串。 |
| resolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | 用於在 [XPath](../../) 表達式中解析命名空間前綴的 [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) 物件。 |

### 返回值

表達式的結果 ([Boolean](../../../system/boolean/)、數字、字串或節點集)。這分別對應到 [Boolean](../../../system/boolean/)、[Double](../../../system/double/)、[String](../../../system/string/) 或 [XPathNodeIterator](../../xpathnodeiterator/) 物件。

## XPathNavigator::Evaluate(SharedPtr\<XPathExpression\>) 方法


評估 [XPathExpression](../../xpathexpression/) 並返回具類型的結果。

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(SharedPtr<XPathExpression> expr)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | 可評估的 [XPathExpression](../../xpathexpression/)。 |

### 返回值

表達式的結果 ([Boolean](../../../system/boolean/)、數字、字串或節點集)。這分別對應到 [Boolean](../../../system/boolean/)、[Double](../../../system/double/)、[String](../../../system/string/) 或 [XPathNodeIterator](../../xpathnodeiterator/) 物件。

## XPathNavigator::Evaluate(SharedPtr\<XPathExpression\>, SharedPtr\<XPathNodeIterator\>) 方法


使用提供的上下文評估 [XPathExpression](../../xpathexpression/)，並返回具類型的結果。

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(SharedPtr<XPathExpression> expr, SharedPtr<XPathNodeIterator> context)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | 可評估的 [XPathExpression](../../xpathexpression/)。 |
| context | [SharedPtr](../../../system/sharedptr/)\<[XPathNodeIterator](../../xpathnodeiterator/)\> | 指向要執行評估的所選節點集合的 [XPathNodeIterator](../../xpathnodeiterator/)。 |

### 返回值

表達式的結果 ([Boolean](../../../system/boolean/)、數字、字串或節點集)。這分別對應到 [Boolean](../../../system/boolean/)、[Double](../../../system/double/)、[String](../../../system/string/) 或 [XPathNodeIterator](../../xpathnodeiterator/) 物件。

## 另見

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [Object](../../../system/object/)
* 類別 [String](../../../system/string/)
* 類別 [XPathNavigator](../)
* 類別 [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* 類別 [XPathExpression](../../xpathexpression/)
* 類別 [XPathNodeIterator](../../xpathnodeiterator/)
* 命名空間 [System::Xml::XPath](../../)
* 函式庫 [Aspose.Slides](../../../)