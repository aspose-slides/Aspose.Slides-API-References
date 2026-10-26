---
title: InsertBefore()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された属性を、指定された参照属性の直前に挿入します。
type: docs
weight: 53
url: /ja/system.xml/xmlattributecollection/insertbefore/
---
## XmlAttributeCollection::InsertBefore(const SharedPtr\<XmlAttribute\>\&, const SharedPtr\<XmlAttribute\>\&) メソッド

指定された属性を、指定された参照属性の直前に挿入します。

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::InsertBefore(const SharedPtr<XmlAttribute> &newNode, const SharedPtr<XmlAttribute> &refNode)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| newNode | const [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\>\& | 挿入する属性。 |
| refNode | const [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\>\& | 参照属性。**newNode** は **refNode** の前に配置されます。 |

### 戻り値

[XmlAttribute](../../xmlattribute/) をコレクションに挿入する値です。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [XmlAttribute](../../xmlattribute/)
* クラス [XmlAttributeCollection](../)
* 名前空間 [System::Xml](../../)
* Library [Aspose.Slides](../../../)