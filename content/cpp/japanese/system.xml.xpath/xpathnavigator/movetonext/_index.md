---
title: MoveToNext()
second_title: Aspose.Slides for C++ API リファレンス
description: 派生クラスでオーバーライドされた場合、XPathNavigator を現在のノードの次の兄弟ノードに移動します。
type: docs
weight: 586
url: /ja/system.xml.xpath/xpathnavigator/movetonext/
---
## XPathNavigator::MoveToNext() メソッド


派生クラスでオーバーライドされた場合、[XPathNavigator](../) を現在のノードの次の兄弟ノードに移動します。

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNext()=0
```


### 戻り値

**true** は [XPathNavigator](../) が次の兄弟ノードへの移動に成功したことを示し、そうでない場合は **false** です。**false** の場合、[XPathNavigator](../) が属性ノード上にあるか、これ以上兄弟が存在しないことを示します。**false** のとき、[XPathNavigator](../) の位置は変更されません。

## XPathNavigator::MoveToNext(String, String) メソッド


指定されたローカル名と名前空間 URI を持つ次の兄弟ノードに [XPathNavigator](../) を移動します。

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNext(String localName, String namespaceURI)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 移動先の次の兄弟ノードのローカル名。 |
| namespaceURI | [String](../../../system/string/) | 移動先の次の兄弟ノードの名前空間 URI。 |

### 戻り値

**true** は [XPathNavigator](../) が次の兄弟ノードへの移動に成功したことを示し、**false** はこれ以上兄弟が存在しないか、[XPathNavigator](../) が属性ノード上にあることを示します。**false** のとき、[XPathNavigator](../) の位置は変更されません。

## XPathNavigator::MoveToNext(XPathNodeType) メソッド


指定された XPathNodeType に一致する現在のノードの次の兄弟ノードへ [XPathNavigator](../) を移動します。

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNext(XPathNodeType type)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | 移動先の兄弟ノードの XPathNodeType。 |

### 戻り値

**true** は [XPathNavigator](../) が次の兄弟ノードへの移動に成功したことを示し、そうでない場合は **false** です。**false** はこれ以上兄弟が存在しないか、[XPathNavigator](../) が属性ノード上にあることを示します。**false** のとき、[XPathNavigator](../) の位置は変更されません。

## 参照

* 列挙体 [XPathNodeType](../../xpathnodetype/)
* クラス [XPathNavigator](../)
* クラス [String](../../../system/string/)
* 名前空間 [System::Xml::XPath](../../)
* ライブラリ [Aspose.Slides](../../../)