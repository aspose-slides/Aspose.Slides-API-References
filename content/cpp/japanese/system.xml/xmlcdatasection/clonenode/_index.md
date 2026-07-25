---
title: CloneNode()
second_title: Aspose.Slides for C++ API リファレンス
description: このノードの複製を作成します。
type: docs
weight: 53
url: /ja/system.xml/xmlcdatasection/clonenode/
---
## XmlCDataSection::CloneNode(bool) メソッド

このノードの複製を作成します。

```cpp
SharedPtr<XmlNode> System::Xml::XmlCDataSection::CloneNode(bool deep) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| deep | **bool** | **true** を指定すると、指定したノード以下のサブツリーを再帰的にクローンします。**false** を指定すると、ノード自体のみをクローンします。CDATA ノードには子が存在しないため、パラメータ設定にかかわらず、クローンされたノードは常にデータ コンテンツを含みます。 |

### 戻り値

クローンされたノード。

## 関連項目

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [XmlNode](../../xmlnode/)
* クラス [XmlCDataSection](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)