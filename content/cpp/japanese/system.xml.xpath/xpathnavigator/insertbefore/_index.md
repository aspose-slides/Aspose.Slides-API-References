---
title: InsertBefore()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在選択されているノードの前に新しい兄弟ノードを作成するために使用される XmlWriter オブジェクトを返します。
type: docs
weight: 911
url: /ja/system.xml.xpath/xpathnavigator/insertbefore/
---
## XPathNavigator::InsertBefore() メソッド

現在選択されているノードの前に新しい兄弟ノードを作成するために使用される [XmlWriter](../../../system.xml/xmlwriter/) オブジェクトを返します。

```cpp
virtual SharedPtr<XmlWriter> System::Xml::XPath::XPathNavigator::InsertBefore()
```

### 戻り値

現在選択されているノードの前に新しい兄弟ノードを作成するために使用される [XmlWriter](../../../system.xml/xmlwriter/) オブジェクト。

## XPathNavigator::InsertBefore(String) メソッド

指定された XML 文字列を使用して、現在選択されているノードの前に新しい兄弟ノードを作成します。

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertBefore(String newSibling)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| newSibling | [String](../../../system/string/) | 新しい兄弟ノードの XML データ文字列。 |

## XPathNavigator::InsertBefore(SharedPtr\<XmlReader\>) メソッド

指定された [XmlReader](../../../system.xml/xmlreader/) オブジェクトの XML コンテンツを使用して、現在選択されているノードの前に新しい兄弟ノードを作成します。

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertBefore(SharedPtr<XmlReader> newSibling)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| newSibling | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | 新しい兄弟ノードの XML データ上に位置する [XmlReader](../../../system.xml/xmlreader/) オブジェクト。 |

## XPathNavigator::InsertBefore(SharedPtr\<XPathNavigator\>) メソッド

指定された [XPathNavigator](../) のノードを使用して、現在選択されているノードの前に新しい兄弟ノードを作成します。

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertBefore(SharedPtr<XPathNavigator> newSibling)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| newSibling | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | 新しい兄弟ノードとして追加するノード上に位置する [XPathNavigator](../) オブジェクト。 |

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [XmlWriter](../../../system.xml/xmlwriter/)
* クラス [XPathNavigator](../)
* クラス [String](../../../system/string/)
* クラス [XmlReader](../../../system.xml/xmlreader/)
* 名前空間 [System::Xml::XPath](../../)
* ライブラリ [Aspose.Slides](../../../)