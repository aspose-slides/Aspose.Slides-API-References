---
title: AppendChild()
second_title: Aspose.Slides for C++ APIリファレンス
description: 現在のノードの子ノードリストの末尾に、1つ以上の新しい子ノードを作成するために使用される XmlWriter オブジェクトを返します。
type: docs
weight: 885
url: /ja/system.xml.xpath/xpathnavigator/appendchild/
---
## XPathNavigator::AppendChild() メソッド

現在のノードの子ノードリストの末尾に、1つ以上の新しい子ノードを作成するために使用される[XmlWriter](../../../system.xml/xmlwriter/)オブジェクトを返します。

```cpp
virtual SharedPtr<XmlWriter> System::Xml::XPath::XPathNavigator::AppendChild()
```

### 戻り値

現在のノードの子ノードリストの末尾に新しい子ノードを作成するために使用される[XmlWriter](../../../system.xml/xmlwriter/)オブジェクトです。

## XPathNavigator::AppendChild(String) メソッド

指定されたXMLデータ文字列を使用して、現在のノードの子ノードリストの末尾に新しい子ノードを作成します。

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChild(String newChild)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| newChild | [String](../../../system/string/) | 新しい子ノードのためのXMLデータ文字列です。 |

## XPathNavigator::AppendChild(SharedPtr\<XmlReader\>) メソッド

指定された[XmlReader](../../../system.xml/xmlreader/)オブジェクトのXML内容を使用して、現在のノードの子ノードリストの末尾に新しい子ノードを作成します。

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChild(SharedPtr<XmlReader> newChild)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | 新しい子ノードのXMLデータ上に位置する[XmlReader](../../../system.xml/xmlreader/)オブジェクトです。 |

## XPathNavigator::AppendChild(SharedPtr\<XPathNavigator\>) メソッド

指定された[XPathNavigator](../)内のノードを使用して、現在のノードの子ノードリストの末尾に新しい子ノードを作成します。

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChild(SharedPtr<XPathNavigator> newChild)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | 新しい子ノードとして追加するノード上に位置する[XPathNavigator](../)オブジェクトです。 |

## 関連項目

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [XmlWriter](../../../system.xml/xmlwriter/)
* クラス [XPathNavigator](../)
* クラス [String](../../../system/string/)
* クラス [XmlReader](../../../system.xml/xmlreader/)
* 名前空間 [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)