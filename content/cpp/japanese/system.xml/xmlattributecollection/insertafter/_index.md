---
title: InsertAfter()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された属性を、指定された参照属性の直後に挿入します。
type: docs
weight: 66
url: /ja/system.xml/xmlattributecollection/insertafter/
---
## XmlAttributeCollection::InsertAfter(const SharedPtr\<XmlAttribute\>\&, const SharedPtr\<XmlAttribute\>\&) メソッド


指定された属性を、指定された参照属性の直後に挿入します。

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::InsertAfter(const SharedPtr<XmlAttribute> &newNode, const SharedPtr<XmlAttribute> &refNode)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| newNode | const [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\>\& | 挿入する属性です。 |
| refNode | const [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\>\& | 参照属性です。**newNode** は **refNode** の後に配置されます。 |

### 戻り値

コレクションに挿入する [XmlAttribute](../../xmlattribute/)。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlAttribute](../../xmlattribute/)
* Class [XmlAttributeCollection](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)