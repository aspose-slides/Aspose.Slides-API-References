---
title: InsertBefore()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたノードを、指定された参照ノードの直前に挿入します。
type: docs
weight: 378
url: /ja/system.xml/xmlnode/insertbefore/
---
## XmlNode::InsertBefore(SharedPtr\<XmlNode\>, SharedPtr\<XmlNode\>) メソッド

指定されたノードを、指定された参照ノードの直前に挿入します。

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNode::InsertBefore(SharedPtr<XmlNode> newChild, SharedPtr<XmlNode> refChild)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../)\> | 挿入するノード。 |
| refChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../)\> | 参照ノード。**newChild** はこのノードの前に配置されます。 |

## 戻り値

挿入されるノード。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [XmlNode](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)