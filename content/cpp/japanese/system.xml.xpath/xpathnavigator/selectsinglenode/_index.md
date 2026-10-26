---
title: SelectSingleNode()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたXPathクエリを使用してXPathNavigator内の単一ノードを選択します。
type: docs
weight: 781
url: /ja/system.xml.xpath/xpathnavigator/selectsinglenode/
---
## XPathNavigator::SelectSingleNode(String) メソッド

指定された[XPath](../../)クエリを使用して[XPathNavigator](../)内の単一ノードを選択します。

```cpp
virtual SharedPtr<XPathNavigator> System::Xml::XPath::XPathNavigator::SelectSingleNode(String xpath)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | [XPath](../../)式を表す[String](../../../system/string/)です。 |

### 戻り値

指定された[XPath](../../)クエリに一致する最初のノードを含む[XPathNavigator](../)オブジェクトです。クエリ結果がない場合は**nullptr**が返されます。

## XPathNavigator::SelectSingleNode(String, SharedPtr\<IXmlNamespaceResolver\>) メソッド

指定された[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)オブジェクトで名前空間プレフィックスを解決し、[XPath](../../)クエリを使用して[XPathNavigator](../)オブジェクト内の単一ノードを選択します。

```cpp
virtual SharedPtr<XPathNavigator> System::Xml::XPath::XPathNavigator::SelectSingleNode(String xpath, SharedPtr<IXmlNamespaceResolver> resolver)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | [XPath](../../)式を表す[String](../../../system/string/)です。 |
| resolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | [XPath](../../)クエリで名前空間プレフィックスを解決するために使用される[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)オブジェクトです。 |

### 戻り値

指定された[XPath](../../)クエリに一致する最初のノードを含む[XPathNavigator](../)オブジェクトです。クエリ結果がない場合は**nullptr**が返されます。

## XPathNavigator::SelectSingleNode(SharedPtr\<XPathExpression\>) メソッド

指定された[XPathExpression](../../xpathexpression/)オブジェクトを使用して[XPathNavigator](../)内の単一ノードを選択します。

```cpp
virtual SharedPtr<XPathNavigator> System::Xml::XPath::XPathNavigator::SelectSingleNode(SharedPtr<XPathExpression> expression)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| expression | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | コンパイル済み[XPath](../../)クエリを含む[XPathExpression](../../xpathexpression/)オブジェクトです。 |

### 戻り値

指定された[XPath](../../)クエリに一致する最初のノードを含む[XPathNavigator](../)オブジェクトです。クエリ結果がない場合は**nullptr**が返されます。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [XPathNavigator](../)
* クラス [String](../../../system/string/)
* クラス [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* クラス [XPathExpression](../../xpathexpression/)
* 名前空間 [System::Xml::XPath](../../)
* ライブラリ [Aspose.Slides](../../../)