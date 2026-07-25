---
title: SelectAncestors()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のノードの祖先ノードのうち、XPathNodeType が一致するものをすべて選択します。
type: docs
weight: 846
url: /ja/system.xml.xpath/xpathnavigator/selectancestors/
---
## XPathNavigator::SelectAncestors(XPathNodeType, bool) メソッド

現在のノードの祖先ノードのうち、XPathNodeType が一致するものをすべて選択します。

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectAncestors(XPathNodeType type, bool matchSelf)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | 祖先ノードの XPathNodeType。 |
| matchSelf | **bool** | 選択にコンテキストノードを含める場合は **true**、それ以外は **false**。 |

### 戻り値

[XPathNodeIterator](../../xpathnodeiterator/) は選択されたノードを含みます。返されるノードは文書順の逆順です。

## XPathNavigator::SelectAncestors(String, String, bool) メソッド

現在のノードの祖先ノードのうち、指定されたローカル名と名前空間 URI を持つものをすべて選択します。

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectAncestors(String name, String namespaceURI, bool matchSelf)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 祖先ノードのローカル名。 |
| namespaceURI | [String](../../../system/string/) | 祖先ノードの名前空間 URI。 |
| matchSelf | **bool** | 選択にコンテキストノードを含める場合は **true**、それ以外は **false**。 |

### 戻り値

[XPathNodeIterator](../../xpathnodeiterator/) は選択されたノードを含みます。返されるノードは文書順の逆順です。

## 参照

* Enum [XPathNodeType](../../xpathnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNodeIterator](../../xpathnodeiterator/)
* Class [XPathNavigator](../)
* Class [String](../../../system/string/)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)