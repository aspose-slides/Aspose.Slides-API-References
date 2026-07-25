---
title: Evaluate()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたXPath式を評価し、型付きの結果を返します。
type: docs
weight: 807
url: /ja/system.xml.xpath/xpathnavigator/evaluate/
---
## XPathNavigator::Evaluate(String) メソッド


指定された[XPath](../../)式を評価し、型付きの結果を返します。

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(String xpath)
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | 評価可能な[XPath](../../)式を表すstringです。 |

### 戻り値

式の結果（[Boolean](../../../system/boolean/)、number、string、またはnode set）。これはそれぞれ[Boolean](../../../system/boolean/)、[Double](../../../system/double/)、[String](../../../system/string/)、[XPathNodeIterator](../../xpathnodeiterator/)オブジェクトに対応します。

## XPathNavigator::Evaluate(String, SharedPtr\<IXmlNamespaceResolver\>) メソッド


提供された[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)オブジェクトを使用して、[XPath](../../)式内の名前空間プレフィックスを解決し、指定された[XPath](../../)式を評価して型付きの結果を返します。

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(String xpath, SharedPtr<IXmlNamespaceResolver> resolver)
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | 評価可能な[XPath](../../)式を表すstringです。 |
| resolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | [XPath](../../)式の名前空間プレフィックスを解決するために使用される[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)オブジェクトです。 |

### 戻り値

式の結果（[Boolean](../../../system/boolean/)、number、string、またはnode set）。これはそれぞれ[Boolean](../../../system/boolean/)、[Double](../../../system/double/)、[String](../../../system/string/)、[XPathNodeIterator](../../xpathnodeiterator/)オブジェクトに対応します。

## XPathNavigator::Evaluate(SharedPtr\<XPathExpression\>) メソッド


[XPathExpression](../../xpathexpression/)を評価し、型付きの結果を返します。

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(SharedPtr<XPathExpression> expr)
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | 評価可能な[XPathExpression](../../xpathexpression/)です。 |

### 戻り値

式の結果（[Boolean](../../../system/boolean/)、number、string、またはnode set）。これはそれぞれ[Boolean](../../../system/boolean/)、[Double](../../../system/double/)、[String](../../../system/string/)、[XPathNodeIterator](../../xpathnodeiterator/)オブジェクトに対応します。

## XPathNavigator::Evaluate(SharedPtr\<XPathExpression\>, SharedPtr\<XPathNodeIterator\>) メソッド


提供されたコンテキストを使用して[XPathExpression](../../xpathexpression/)を評価し、型付きの結果を返します。

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(SharedPtr<XPathExpression> expr, SharedPtr<XPathNodeIterator> context)
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | 評価可能な[XPathExpression](../../xpathexpression/)です。 |
| context | [SharedPtr](../../../system/sharedptr/)\<[XPathNodeIterator](../../xpathnodeiterator/)\> | 評価が実行される選択されたノードセットを指す[XPathNodeIterator](../../xpathnodeiterator/)です。 |

### 戻り値

式の結果（[Boolean](../../../system/boolean/)、number、string、またはnode set）。これはそれぞれ[Boolean](../../../system/boolean/)、[Double](../../../system/double/)、[String](../../../system/string/)、[XPathNodeIterator](../../xpathnodeiterator/)オブジェクトに対応します。

## 関連項目

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [Object](../../../system/object/)
* クラス [String](../../../system/string/)
* クラス [XPathNavigator](../)
* クラス [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* クラス [XPathExpression](../../xpathexpression/)
* クラス [XPathNodeIterator](../../xpathnodeiterator/)
* 名前空間 [System::Xml::XPath](../../)
* ライブラリ [Aspose.Slides](../../../)