---
title: RemoveAttributeAt()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたインデックスの属性ノードを要素から削除します。（削除された属性にデフォルト値がある場合、直ちに置き換えられます。）
type: docs
weight: 339
url: /ja/system.xml/xmlelement/removeattributeat/
---
## XmlElement::RemoveAttributeAt(int32_t) メソッド

指定されたインデックスの属性ノードを要素から削除します。（削除された属性にデフォルト値がある場合、直ちに置き換えられます。）

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlElement::RemoveAttributeAt(int32_t i)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| i | **int32_t** | 削除するノードのインデックス。最初のノードのインデックスは 0 です。 |

### 戻り値

削除された属性ノード、または指定されたインデックスにノードが存在しない場合は **nullptr** が返されます。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlElement](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)