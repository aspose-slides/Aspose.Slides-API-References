---
title: Remove()
second_title: Aspose.Slides for C++ API リファレンス
description: XmlSchemaSet から指定された XML Schema 定義言語 (XSD) スキーマを削除します。
type: docs
weight: 170
url: /ja/system.xml.schema/xmlschemaset/remove/
---
## XmlSchemaSet::Remove(const SharedPtr\<XmlSchema\>\&) method


指定された XML [Schema](../../) 定義言語 (XSD) スキーマを [XmlSchemaSet](../) から削除します。

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Remove(const SharedPtr<XmlSchema> &schema)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | [XmlSchemaSet](../) から削除対象となる [XmlSchema](../../xmlschema/) オブジェクト。 |

### 戻り値

[XmlSchemaSet](../) から削除された [XmlSchema](../../xmlschema/) オブジェクト、または [XmlSchemaSet](../) にスキーマが見つからなかった場合は **nullptr**。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../../xmlschema/)
* Class [XmlSchemaSet](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)