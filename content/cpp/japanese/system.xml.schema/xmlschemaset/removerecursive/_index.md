---
title: RemoveRecursive()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された XML Schema 定義言語（XSD）スキーマと、そのインポートされたすべてのスキーマを XmlSchemaSet から削除します。
type: docs
weight: 183
url: /ja/system.xml.schema/xmlschemaset/removerecursive/
---
## XmlSchemaSet::RemoveRecursive(const SharedPtr\<XmlSchema\>\&) method

指定された XML [Schema](../../) 定義言語（XSD）スキーマと、そのインポートされたすべてのスキーマを [XmlSchemaSet](../) から削除します。

```cpp
bool System::Xml::Schema::XmlSchemaSet::RemoveRecursive(const SharedPtr<XmlSchema> &schemaToRemove)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| schemaToRemove | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | [XmlSchema](../../xmlschema/) オブジェクトを [XmlSchemaSet](../) から削除します。 |

### 戻り値

**true** は、[XmlSchema](../../xmlschema/) オブジェクトとそのすべてのインポートが正常に削除された場合を示し、そうでない場合は **false** です。

## 関連項目

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [XmlSchema](../../xmlschema/)
* クラス [XmlSchemaSet](../)
* 名前空間 [System::Xml::Schema](../../)
* ライブラリ [Aspose.Slides](../../../)