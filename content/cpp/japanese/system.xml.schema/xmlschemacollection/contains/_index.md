---
title: Contains()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された XmlSchema の targetNamespace がコレクションに含まれているかどうかを示す値を返します。
type: docs
weight: 66
url: /ja/system.xml.schema/xmlschemacollection/contains/
---
## XmlSchemaCollection::Contains(const SharedPtr\<XmlSchema\>\&) メソッド

指定された [XmlSchema](../../xmlschema/) の **targetNamespace** がコレクションに含まれているかどうかを示す値を返します。

```cpp
bool System::Xml::Schema::XmlSchemaCollection::Contains(const SharedPtr<XmlSchema> &schema)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | [XmlSchema](../../xmlschema/) オブジェクト。 |

### 戻り値

**true** は、同じ **targetNamespace** を持つスキーマがコレクションに存在する場合です。そうでない場合は **false** です。

## XmlSchemaCollection::Contains(const String\&) メソッド

指定された名前空間を持つスキーマがコレクションに含まれているかどうかを示す値を返します。

```cpp
bool System::Xml::Schema::XmlSchemaCollection::Contains(const String &ns)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | スキーマに関連付けられた名前空間 URI。XML スキーマの場合、通常はターゲット名前空間です。 |

### 戻り値

**true** は、指定された名前空間を持つスキーマがコレクションにある場合です。そうでない場合は **false** です。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [XmlSchema](../../xmlschema/)
* クラス [XmlSchemaCollection](../)
* クラス [String](../../../system/string/)
* 名前空間 [System::Xml::Schema](../../)
* ライブラリ [Aspose.Slides](../../../)