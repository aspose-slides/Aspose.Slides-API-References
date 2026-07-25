---
title: InsertAfter()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたノードを、指定された参照ノードの直後に挿入します。
type: docs
weight: 391
url: /ja/system.xml/xmlnode/insertafter/
---
## XmlNode::InsertAfter(SharedPtr\<XmlNode\>, SharedPtr\<XmlNode\>) メソッド

指定されたノードを、指定された参照ノードの直後に挿入します。

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNode::InsertAfter(SharedPtr<XmlNode> newChild, SharedPtr<XmlNode> refChild)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../)\> | 挿入するノード。 |
| refChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../)\> | 参照ノード。**newChild** は **refChild** の後に配置されます。 |

### 戻り値

挿入されるノード。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [XmlNode](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)