---
title: MoveToNextNamespace()
second_title: Aspose.Slides for C++ API リファレンス
description: 派生クラスでオーバーライドされた場合、指定された XPathNamespaceScope に一致する次の名前空間ノードへ XPathNavigator を移動します。
type: docs
weight: 573
url: /ja/system.xml.xpath/xpathnavigator/movetonextnamespace/
---
## XPathNavigator::MoveToNextNamespace(XPathNamespaceScope) メソッド

派生クラスでオーバーライドされた場合、[XPathNavigator](../) を指定された XPathNamespaceScope に一致する次の名前空間ノードへ移動します。

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNextNamespace(XPathNamespaceScope namespaceScope)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| namespaceScope | [XPathNamespaceScope](../../xpathnamespacescope/) | 名前空間のスコープを記述する XPathNamespaceScope 値。 |

### 戻り値

**true** が、[XPathNavigator](../) が次の名前空間ノードへの移動に成功した場合に返されます。そうでない場合は **false** が返されます。**false** の場合、[XPathNavigator](../) の位置は変更されません。

## XPathNavigator::MoveToNextNamespace() メソッド

[XPathNavigator](../) を次の名前空間ノードへ移動します。

```cpp
bool System::Xml::XPath::XPathNavigator::MoveToNextNamespace()
```

### 戻り値

**true** が、[XPathNavigator](../) が次の名前空間ノードへの移動に成功した場合に返されます。そうでない場合は **false** が返されます。**false** の場合、[XPathNavigator](../) の位置は変更されません。

## 参照

* 列挙体 [XPathNamespaceScope](../../xpathnamespacescope/)
* クラス [XPathNavigator](../)
* 名前空間 [System::Xml::XPath](../../)
* ライブラリ [Aspose.Slides](../../../)