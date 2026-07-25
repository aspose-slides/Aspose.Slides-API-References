---
title: MoveToFirstNamespace()
second_title: Aspose.Slides for C++ API リファレンス
description: 派生クラスでオーバーライドされた場合、指定された XPathNamespaceScope に一致する最初の名前空間ノードへ XPathNavigator を移動します。
type: docs
weight: 560
url: /ja/system.xml.xpath/xpathnavigator/movetofirstnamespace/
---
## XPathNavigator::MoveToFirstNamespace(XPathNamespaceScope) メソッド


派生クラスでオーバーライドされた場合、[XPathNavigator](../) を指定された XPathNamespaceScope に一致する最初の名前空間ノードへ移動します。

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFirstNamespace(XPathNamespaceScope namespaceScope)=0
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| namespaceScope | [XPathNamespaceScope](../../xpathnamespacescope/) | 名前空間スコープを表す XPathNamespaceScope 値。 |

### 戻り値

**true** は [XPathNavigator](../) が最初の名前空間ノードへの移動に成功した場合です。そうでない場合は **false** です。**false** の場合、[XPathNavigator](../) の位置は変更されません。

## XPathNavigator::MoveToFirstNamespace() メソッド


現在のノードの最初の名前空間ノードへ [XPathNavigator](../) を移動します。

```cpp
bool System::Xml::XPath::XPathNavigator::MoveToFirstNamespace()
```


### 戻り値

**true** は [XPathNavigator](../) が最初の名前空間ノードへの移動に成功した場合です。そうでない場合は **false** です。**false** の場合、[XPathNavigator](../) の位置は変更されません。

## 参照

* 列挙体 [XPathNamespaceScope](../../xpathnamespacescope/)
* クラス [XPathNavigator](../)
* 名前空間 [System::Xml::XPath](../../)
* ライブラリ [Aspose.Slides](../../../)