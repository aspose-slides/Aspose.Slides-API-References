---
title: InsertAfter()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたノードを、指定された参照ノードの直後に挿入します。
type: docs
weight: 222
url: /ja/system.xml/xmlattribute/insertafter/
---
## XmlAttribute::InsertAfter(SharedPtr\<XmlNode\>, SharedPtr\<XmlNode\>) メソッド

指定されたノードを、指定された参照ノードの直後に挿入します。

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttribute::InsertAfter(SharedPtr<XmlNode> newChild, SharedPtr<XmlNode> refChild) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | 挿入する[XmlNode](../../xmlnode/)。 |
| refChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | 参照ノードである[XmlNode](../../xmlnode/)。**newChild**は**refChild**の後に配置されます。 |

### 戻り値

挿入された[XmlNode](../../xmlnode/)。

## 参照項目

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [XmlNode](../../xmlnode/)
* クラス [XmlAttribute](../)
* 名前空間 [System::Xml](../../)
* Library [Aspose.Slides](../../../)