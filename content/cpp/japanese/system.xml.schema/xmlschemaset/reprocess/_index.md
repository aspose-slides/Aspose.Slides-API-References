---
title: Reprocess()
second_title: Aspose.Slides for C++ API リファレンス
description: XmlSchemaSet に既に存在する XML スキーマ定義言語（XSD）スキーマを再処理します。
type: docs
weight: 222
url: /ja/system.xml.schema/xmlschemaset/reprocess/
---
## XmlSchemaSet::Reprocess(SharedPtr\<XmlSchema\>) メソッド

既に[XmlSchemaSet](../)に存在するXML [Schema](../../) 定義言語（XSD）スキーマを再処理します。

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Reprocess(SharedPtr<XmlSchema> schema)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| schema | [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\> | 再処理するスキーマ。 |

### 戻り値

スキーマが有効な場合、[XmlSchema](../../xmlschema/) オブジェクトが返されます。スキーマが無効で、ValidationEventHandler が指定されている場合、**nullptr** が返され、適切な検証イベントが発生します。そうでない場合は XmlSchemaException がスローされます。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [XmlSchema](../../xmlschema/)
* クラス [XmlSchemaSet](../)
* 名前空間 [System::Xml::Schema](../../)
* ライブラリ [Aspose.Slides](../../../)