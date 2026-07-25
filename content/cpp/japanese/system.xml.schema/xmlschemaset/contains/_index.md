---
title: Contains()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたターゲット名前空間 URI を持つ XML スキーマ定義言語 (XSD) スキーマが XmlSchemaSet にあるかどうかを示します。
type: docs
weight: 196
url: /ja/system.xml.schema/xmlschemaset/contains/
---
## XmlSchemaSet::Contains(String) メソッド


指定されたターゲット名前空間URIを持つXML [Schema](../../) 定義言語 (XSD) スキーマが [XmlSchemaSet](../) にあるかどうかを示します。

```cpp
bool System::Xml::Schema::XmlSchemaSet::Contains(String targetNamespace)
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| targetNamespace | [String](../../../system/string/) | スキーマの **targetNamespace** プロパティ。 |

### 戻り値

**true** if a schema with the specified target namespace URI is in the [XmlSchemaSet](../); otherwise, **false**.

## XmlSchemaSet::Contains(const SharedPtr\<XmlSchema\>\&) メソッド


指定されたXML [Schema](../../) 定義言語 (XSD) [XmlSchema](../../xmlschema/) オブジェクトが [XmlSchemaSet](../) にあるかどうかを示します。

```cpp
bool System::Xml::Schema::XmlSchemaSet::Contains(const SharedPtr<XmlSchema> &schema)
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | [XmlSchema](../../xmlschema/) オブジェクト。 |

### 戻り値

**true** if the [XmlSchema](../../xmlschema/) object is in the [XmlSchemaSet](../); otherwise, **false**.

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [String](../../../system/string/)
* クラス [XmlSchemaSet](../)
* クラス [XmlSchema](../../xmlschema/)
* 名前空間 [System::Xml::Schema](../../)
* ライブラリ [Aspose.Slides](../../../)