---
title: MoveToNamespace()
second_title: Aspose.Slides for C++ API リファレンス
description: XPathNavigator を指定された名前空間プレフィックスを持つ名前空間ノードへ移動します。
type: docs
weight: 547
url: /ja/system.xml.xpath/xpathnavigator/movetonamespace/
---
## XPathNavigator::MoveToNamespace(String) メソッド

[XPathNavigator](../) を指定された名前空間プレフィックスを持つ名前空間ノードへ移動します。

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNamespace(String name)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 名前空間ノードの名前空間プレフィックス。 |

### 戻り値

**true** は、[XPathNavigator](../) が指定された名前空間への移動に成功した場合です。**false** は、一致する名前空間ノードが見つからなかった場合、または [XPathNavigator](../) が要素ノード上に位置していない場合です。**false** の場合、[XPathNavigator](../) の位置は変わりません。

## 関連項目

* クラス [String](../../../system/string/)
* クラス [XPathNavigator](../)
* 名前空間 [System::Xml::XPath](../../)
* ライブラリ [Aspose.Slides](../../../)