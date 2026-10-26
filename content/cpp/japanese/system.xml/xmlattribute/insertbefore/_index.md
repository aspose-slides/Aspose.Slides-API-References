---
title: InsertBefore()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたノードを、指定された参照ノードの直前に挿入します。
type: docs
weight: 209
url: /ja/system.xml/xmlattribute/insertbefore/
---
## XmlAttribute::InsertBefore(SharedPtr\<XmlNode\>, SharedPtr\<XmlNode\>) メソッド

指定されたノードを、指定された参照ノードの直前に挿入します。

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttribute::InsertBefore(SharedPtr<XmlNode> newChild, SharedPtr<XmlNode> refChild) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | 挿入する [XmlNode](../../xmlnode/)。 |
| refChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | [XmlNode](../../xmlnode/) は参照ノードです。**newChild** はこのノードの前に配置されます。 |

### 戻り値

挿入された [XmlNode](../../xmlnode/)。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [XmlNode](../../xmlnode/)
* クラス [XmlAttribute](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)