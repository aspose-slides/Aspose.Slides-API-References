---
title: Add()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された URL の XML Schema 定義言語 (XSD) スキーマを XmlSchemaSet に追加します。
type: docs
weight: 157
url: /ja/system.xml.schema/xmlschemaset/add/
---
## XmlSchemaSet::Add(String, const String\&) method

指定された URL の XML [Schema](../../) 定義言語 (XSD) スキーマを [XmlSchemaSet](../) に追加します。

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Add(String targetNamespace, const String &schemaUri)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| targetNamespace | [String](../../../system/string/) | スキーマの **targetNamespace** 値、またはスキーマで指定された **targetNamespace** を使用する場合は **nullptr**。 |
| schemaUri | const [String](../../../system/string/)\& | 読み込むスキーマを指定する URL。 |

### 戻り値

スキーマが有効な場合は [XmlSchema](../../xmlschema/) オブジェクトが返されます。スキーマが無効で ValidationEventHandler が指定されている場合は **nullptr** が返され、適切な検証イベントが発生します。その他の場合は XmlSchemaException がスローされます。

## XmlSchemaSet::Add(String, const SharedPtr\<XmlReader\>\&) method

[XmlReader](../../../system.xml/xmlreader/) に含まれる XML [Schema](../../) 定義言語 (XSD) スキーマを [XmlSchemaSet](../) に追加します。

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Add(String targetNamespace, const SharedPtr<XmlReader> &schemaDocument)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| targetNamespace | [String](../../../system/string/) | スキーマの **targetNamespace** 値、またはスキーマで指定された **targetNamespace** を使用する場合は **nullptr**。 |
| schemaDocument | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | [XmlReader](../../../system.xml/xmlreader/) オブジェクト。 |

### 戻り値

スキーマが有効な場合は [XmlSchema](../../xmlschema/) オブジェクトが返されます。スキーマが無効で ValidationEventHandler が指定されている場合は **nullptr** が返され、適切な検証イベントが発生します。その他の場合は XmlSchemaException がスローされます。

## XmlSchemaSet::Add(const SharedPtr\<XmlSchemaSet\>\&) method

指定された [XmlSchemaSet](../) 内のすべての XML [Schema](../../) 定義言語 (XSD) スキーマを [XmlSchemaSet](../) に追加します。

```cpp
void System::Xml::Schema::XmlSchemaSet::Add(const SharedPtr<XmlSchemaSet> &schemas)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| schemas | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaSet](../)\>\& | [XmlSchemaSet](../) オブジェクト。 |

## XmlSchemaSet::Add(const SharedPtr\<XmlSchema\>\&) method

指定された [XmlSchema](../../xmlschema/) を [XmlSchemaSet](../) に追加します。

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Add(const SharedPtr<XmlSchema> &schema)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | [XmlSchema](../../xmlschema/) オブジェクトを [XmlSchemaSet](../) に追加します。 |

### 戻り値

スキーマが有効な場合は [XmlSchema](../../xmlschema/) オブジェクトが返されます。スキーマが無効で ValidationEventHandler が指定されている場合は **nullptr** が返され、適切な検証イベントが発生します。その他の場合は XmlSchemaException がスローされます。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../../xmlschema/)
* Class [String](../../../system/string/)
* Class [XmlSchemaSet](../)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)