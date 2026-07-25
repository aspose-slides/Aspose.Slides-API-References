---
title: SelectDescendants()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のノードの子孫ノードで、マッチする XPathNodeType を持つものをすべて選択します。
type: docs
weight: 859
url: /ja/system.xml.xpath/xpathnavigator/selectdescendants/
---
## XPathNavigator::SelectDescendants(XPathNodeType, bool) メソッド

現在のノードの子孫ノードで、指定された XPathNodeType と一致するものをすべて選択します。

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectDescendants(XPathNodeType type, bool matchSelf)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | 子孫ノードの XPathNodeType。 |
| matchSelf | **bool** | 選択にコンテキスト ノードを含める場合は **true**、そうでない場合は **false**。 |

### 戻り値

選択されたノードを含む [XPathNodeIterator](../../xpathnodeiterator/)。

## XPathNavigator::SelectDescendants(String, String, bool) メソッド

現在のノードの子孫ノードで、指定されたローカル名と名前空間 URI を持つものをすべて選択します。

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectDescendants(String name, String namespaceURI, bool matchSelf)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 子孫ノードのローカル名。 |
| namespaceURI | [String](../../../system/string/) | 子孫ノードの名前空間 URI。 |
| matchSelf | **bool** | 選択にコンテキスト ノードを含める場合は **true**、そうでない場合は **false**。 |

### 戻り値

選択されたノードを含む [XPathNodeIterator](../../xpathnodeiterator/)。

## 参照

* 列挙体 [XPathNodeType](../../xpathnodetype/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [XPathNodeIterator](../../xpathnodeiterator/)
* クラス [XPathNavigator](../)
* クラス [String](../../../system/string/)
* 名前空間 [System::Xml::XPath](../../)
* ライブラリ [Aspose.Slides](../../../)