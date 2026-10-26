---
title: CloneNode()
second_title: Aspose.Slides for C++ APIリファレンス
description: このノードの複製を作成します。
type: docs
weight: 157
url: /ja/system.xml/xmldeclaration/clonenode/
---
## XmlDeclaration::CloneNode(bool) method

このノードの複製を作成します。

```cpp
SharedPtr<XmlNode> System::Xml::XmlDeclaration::CloneNode(bool deep) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| deep | **bool** | **true** を指定すると、指定されたノード以下のサブツリーを再帰的にクローンします。**false** を指定すると、ノード自体のみをクローンします。[XmlDeclaration](../) ノードは子を持たないため、パラメータ設定に関係なくクローンされたノードには常にデータ値が含まれます。 |

### 戻り値

クローンされたノード。

## 参照

* typedef [SharedPtr](../../../system/sharedptr/)
* クラス [XmlNode](../../xmlnode/)
* クラス [XmlDeclaration](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)