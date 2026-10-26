---
title: ReplaceSelf()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された文字列の内容で現在のノードを置き換えます。
type: docs
weight: 950
url: /ja/system.xml.xpath/xpathnavigator/replaceself/
---
## XPathNavigator::ReplaceSelf(String) メソッド

現在のノードを指定された文字列の内容で置き換えます。

```cpp
virtual void System::Xml::XPath::XPathNavigator::ReplaceSelf(String newNode)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| newNode | [String](../../../system/string/) | 新しいノードの XML データ文字列。 |

## XPathNavigator::ReplaceSelf(SharedPtr\<XmlReader\>) メソッド

現在のノードを指定された [XmlReader](../../../system.xml/xmlreader/) オブジェクトの内容で置き換えます。

```cpp
virtual void System::Xml::XPath::XPathNavigator::ReplaceSelf(SharedPtr<XmlReader> newNode)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| newNode | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | 新しいノードの XML データ上に位置する [XmlReader](../../../system.xml/xmlreader/) オブジェクト。 |

## XPathNavigator::ReplaceSelf(SharedPtr\<XPathNavigator\>) メソッド

現在のノードを指定された [XPathNavigator](../) オブジェクトの内容で置き換えます。

```cpp
virtual void System::Xml::XPath::XPathNavigator::ReplaceSelf(SharedPtr<XPathNavigator> newNode)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| newNode | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | 新しいノード上に位置する [XPathNavigator](../) オブジェクト。 |

## 参照

* タイプ定義 [SharedPtr](../../../system/sharedptr/)
* クラス [String](../../../system/string/)
* クラス [XPathNavigator](../)
* クラス [XmlReader](../../../system.xml/xmlreader/)
* 名前空間 [System::Xml::XPath](../../)
* ライブラリ [Aspose.Slides](../../../)