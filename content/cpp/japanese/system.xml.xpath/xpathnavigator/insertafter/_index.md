---
title: InsertAfter()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在選択されているノードの後に新しい兄弟ノードを作成するために使用される XmlWriter オブジェクトを返します。
type: docs
weight: 898
url: /ja/system.xml.xpath/xpathnavigator/insertafter/
---
## XPathNavigator::InsertAfter() メソッド

現在選択されているノードの後に新しい兄弟ノードを作成するために使用される [XmlWriter](../../../system.xml/xmlwriter/) オブジェクトを返します。

```cpp
virtual SharedPtr<XmlWriter> System::Xml::XPath::XPathNavigator::InsertAfter()
```

### 戻り値

現在選択されているノードの後に新しい兄弟ノードを作成するために使用される [XmlWriter](../../../system.xml/xmlwriter/) オブジェクト。

## XPathNavigator::InsertAfter(String) メソッド

指定された XML 文字列を使用して、現在選択されているノードの後に新しい兄弟ノードを作成します。

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertAfter(String newSibling)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| newSibling | [String](../../../system/string/) | 新しい兄弟ノードの XML データ文字列。 |

## XPathNavigator::InsertAfter(SharedPtr\<XmlReader\>) メソッド

指定された [XmlReader](../../../system.xml/xmlreader/) オブジェクトの XML 内容を使用して、現在選択されているノードの後に新しい兄弟ノードを作成します。

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertAfter(SharedPtr<XmlReader> newSibling)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| newSibling | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | [XmlReader](../../../system.xml/xmlreader/) オブジェクトは新しい兄弟ノードの XML データ上に位置付けられます。 |

## XPathNavigator::InsertAfter(SharedPtr\<XPathNavigator\>) メソッド

指定された [XPathNavigator](../) オブジェクトのノードを使用して、現在選択されているノードの後に新しい兄弟ノードを作成します。

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertAfter(SharedPtr<XPathNavigator> newSibling)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| newSibling | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | [XPathNavigator](../) オブジェクトは新しい兄弟ノードとして追加するノード上に位置付けられます。 |

## 参考

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [XmlWriter](../../../system.xml/xmlwriter/)
* クラス [XPathNavigator](../)
* クラス [String](../../../system/string/)
* クラス [XmlReader](../../../system.xml/xmlreader/)
* 名前空間 [System::Xml::XPath](../../)
* ライブラリ [Aspose.Slides](../../../)