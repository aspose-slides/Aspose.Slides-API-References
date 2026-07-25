---
title: CloneNode()
second_title: Aspose.Slides for C++ API リファレンス
description: このノードの複製を作成します。
type: docs
weight: 79
url: /ja/system.xml/xmlwhitespace/clonenode/
---
## XmlWhitespace::CloneNode(bool) メソッド


このノードの複製を作成します。

```cpp
SharedPtr<XmlNode> System::Xml::XmlWhitespace::CloneNode(bool deep) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| deep | **bool** | **true** は指定されたノード以下のサブツリーを再帰的にクローンします。**false** はノード自体のみをクローンします。白空白ノードの場合、クローンされたノードは常にデータ値を含みます。パラメータ設定に関係なく。 |

### 戻り値

クローンされたノード。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [XmlNode](../../xmlnode/)
* クラス [XmlWhitespace](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)