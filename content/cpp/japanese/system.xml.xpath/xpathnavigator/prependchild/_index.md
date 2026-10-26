---
title: PrependChild()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のノードの子ノードリストの先頭に新しい子ノードを作成するために使用される XmlWriter オブジェクトを返します。
type: docs
weight: 872
url: /ja/system.xml.xpath/xpathnavigator/prependchild/
---
## XPathNavigator::PrependChild() メソッド

現在のノードの子ノードリストの先頭に新しい子ノードを作成するために使用される [XmlWriter](../../../system.xml/xmlwriter/) オブジェクトを返します。

```cpp
virtual SharedPtr<XmlWriter> System::Xml::XPath::XPathNavigator::PrependChild()
```

### 戻り値

現在のノードの子ノードリストの先頭に新しい子ノードを作成するために使用される [XmlWriter](../../../system.xml/xmlwriter/) オブジェクトです。

## XPathNavigator::PrependChild(String) メソッド

指定された XML 文字列を使用して、現在のノードの子ノードリストの先頭に新しい子ノードを作成します。

```cpp
virtual void System::Xml::XPath::XPathNavigator::PrependChild(String newChild)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| newChild | [String](../../../system/string/) | 新しい子ノードの XML データ文字列です。 |

## XPathNavigator::PrependChild(SharedPtr\<XmlReader\>) メソッド

指定された [XmlReader](../../../system.xml/xmlreader/) オブジェクトの XML 内容を使用して、現在のノードの子ノードリストの先頭に新しい子ノードを作成します。

```cpp
virtual void System::Xml::XPath::XPathNavigator::PrependChild(SharedPtr<XmlReader> newChild)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | 新しい子ノードの XML データを指す位置にある [XmlReader](../../../system.xml/xmlreader/) オブジェクトです。 |

## XPathNavigator::PrependChild(SharedPtr\<XPathNavigator\>) メソッド

指定された [XPathNavigator](../) オブジェクト内のノードを使用して、現在のノードの子ノードリストの先頭に新しい子ノードを作成します。

```cpp
virtual void System::Xml::XPath::XPathNavigator::PrependChild(SharedPtr<XPathNavigator> newChild)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | 新しい子ノードとして追加するノードを指す位置にある [XPathNavigator](../) オブジェクトです。 |

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [XmlWriter](../../../system.xml/xmlwriter/)
* クラス [XPathNavigator](../)
* クラス [String](../../../system/string/)
* クラス [XmlReader](../../../system.xml/xmlreader/)
* 名前空間 [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)