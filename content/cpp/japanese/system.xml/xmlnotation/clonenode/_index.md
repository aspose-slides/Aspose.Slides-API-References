---
title: CloneNode()
second_title: Aspose.Slides for C++ API リファレンス
description: このノードの複製を作成します。Notation ノードはクローンできません。XmlNotation オブジェクトでこのメソッドを呼び出すと例外がスローされます。
type: docs
weight: 118
url: /ja/system.xml/xmlnotation/clonenode/
---
## XmlNotation::CloneNode(bool) メソッド

このノードの複製を作成します。Notation ノードはクローンできません。[XmlNotation](../) オブジェクトでこのメソッドを呼び出すと例外がスローされます。

```cpp
SharedPtr<XmlNode> System::Xml::XmlNotation::CloneNode(bool deep) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| deep | **bool** | **true** は、指定されたノード以下のサブツリーを再帰的にクローンします。**false** は、ノード自体のみをクローンします。 |

### 戻り値

メソッドが呼び出されたノードの [XmlNode](../../xmlnode/) コピー。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [XmlNode](../../xmlnode/)
* クラス [XmlNotation](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)