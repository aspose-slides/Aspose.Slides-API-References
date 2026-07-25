---
title: Select()
second_title: C++ 用 Aspose.Slides API リファレンス
description: 指定された XPath 式を使用してノード集合を選択します。
type: docs
weight: 794
url: /ja/system.xml.xpath/xpathnavigator/select/
---
## XPathNavigator::Select(String) メソッド

指定された[XPath](../../)式を使用してノード集合を選択します。

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::Select(String xpath)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | [String](../../../system/string/) は [XPath](../../) 式を表すものです。 |

### 戻り値

選択されたノード集合を指す[XPathNodeIterator](../../xpathnodeiterator/)です。

## XPathNavigator::Select(String, SharedPtr\<IXmlNamespaceResolver\>) メソッド

指定された[XPath](../../)式と、名前空間プレフィックスを解決するために指定された[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)オブジェクトを使用してノード集合を選択します。

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::Select(String xpath, SharedPtr<IXmlNamespaceResolver> resolver)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | [String](../../../system/string/) は [XPath](../../) 式を表すものです。 |
| resolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) は名前空間プレフィックスを解決するために使用されるオブジェクトです。 |

### 戻り値

選択されたノード集合を指す[XPathNodeIterator](../../xpathnodeiterator/)です。

## XPathNavigator::Select(SharedPtr\<XPathExpression\>) メソッド

指定された[XPathExpression](../../xpathexpression/) を使用してノード集合を選択します。

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::Select(SharedPtr<XPathExpression> expr)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | [XPathExpression](../../xpathexpression/) は、コンパイルされた[XPath](../../)クエリを含むオブジェクトです。 |

### 戻り値

選択されたノード集合を指す[XPathNodeIterator](../../xpathnodeiterator/)です。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [XPathNodeIterator](../../xpathnodeiterator/)
* クラス [String](../../../system/string/)
* クラス [XPathNavigator](../)
* クラス [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* クラス [XPathExpression](../../xpathexpression/)
* 名前空間 [System::Xml::XPath](../../)
* ライブラリ [Aspose.Slides](../../../)