---
title: MoveToChild()
second_title: Aspose.Slides の C++ API リファレンス
description: 指定されたローカル名と名前空間URIを持つ子ノードにXPathNavigatorを移動します。
type: docs
weight: 690
url: /ja/system.xml.xpath/xpathnavigator/movetochild/
---
## XPathNavigator::MoveToChild(String, String) メソッド

指定されたローカル名と名前空間URIを持つ子ノードへ [XPathNavigator](../) を移動します。

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToChild(String localName, String namespaceURI)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 移動先の子ノードのローカル名。 |
| namespaceURI | [String](../../../system/string/) | 移動先の子ノードの名前空間URI。 |

### 戻り値

**true** は [XPathNavigator](../) が子ノードへの移動に成功した場合; それ以外の場合は **false**。**false** の場合、[XPathNavigator](../) の位置は変更されません。

## XPathNavigator::MoveToChild(XPathNodeType) メソッド

指定されたXPathNodeType の子ノードへ [XPathNavigator](../) を移動します。

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToChild(XPathNodeType type)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | 移動先の子ノードのXPathNodeType。 |

### 戻り値

**true** は [XPathNavigator](../) が子ノードへの移動に成功した場合; それ以外の場合は **false**。**false** の場合、[XPathNavigator](../) の位置は変更されません。

## 参照

* 列挙型 [XPathNodeType](../../xpathnodetype/)
* クラス [String](../../../system/string/)
* クラス [XPathNavigator](../)
* 名前空間 [System::Xml::XPath](../../)
* ライブラリ [Aspose.Slides](../../../)