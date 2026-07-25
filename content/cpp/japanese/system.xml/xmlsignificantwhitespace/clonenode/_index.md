---
title: CloneNode()
second_title: Aspose.Slides for C++ API リファレンス
description: このノードの複製を作成します。
type: docs
weight: 79
url: /ja/system.xml/xmlsignificantwhitespace/clonenode/
---
## XmlSignificantWhitespace::CloneNode(bool) メソッド

このノードの複製を作成します。

```cpp
SharedPtr<XmlNode> System::Xml::XmlSignificantWhitespace::CloneNode(bool deep) override
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| deep | **bool** | **true**：指定されたノード以下のサブツリーを再帰的にクローンします。**false**：ノード自体のみをクローンします。重要な空白ノードの場合、クローンされたノードは常にデータ値を含み、パラメーター設定に関係なく含まれます。 |

### 戻り値

クローンされたノードです。

## 関連項目

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [XmlNode](../../xmlnode/)
* クラス [XmlSignificantWhitespace](../)
* 名前空間 [System::Xml](../../)
* Library [Aspose.Slides](../../../)