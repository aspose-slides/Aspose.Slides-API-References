---
title: InferSchema()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された XmlReader オブジェクトに含まれる XML 文書から XML Schema Definition Language (XSD) スキーマを推測します。
type: docs
weight: 66
url: /ja/system.xml.schema/xmlschemainference/inferschema/
---
## XmlSchemaInference::InferSchema(const SharedPtr\<XmlReader\>\&) メソッド


指定された [XmlReader](../../../system.xml/xmlreader/) オブジェクトに含まれる XML 文書から XML [Schema](../../) 定義言語 (XSD) スキーマを推測します。

```cpp
SharedPtr<XmlSchemaSet> System::Xml::Schema::XmlSchemaInference::InferSchema(const SharedPtr<XmlReader> &instanceDocument)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| instanceDocument | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | XML スキーマを推測するための XML 文書を含む [XmlReader](../../../system.xml/xmlreader/) オブジェクト |

### 戻り値

推測されたスキーマを含む [XmlSchemaSet](../../xmlschemaset/) オブジェクト。

## XmlSchemaInference::InferSchema(const SharedPtr\<XmlReader\>\&, SharedPtr\<XmlSchemaSet\>) メソッド


指定された [XmlReader](../../../system.xml/xmlreader/) オブジェクトに含まれる XML 文書から XML [Schema](../../) 定義言語 (XSD) スキーマを推測し、同じターゲット名前空間を持つ [XmlSchemaSet](../../xmlschemaset/) オブジェクトにある既存のスキーマを使用して推測スキーマを洗練します。

```cpp
SharedPtr<XmlSchemaSet> System::Xml::Schema::XmlSchemaInference::InferSchema(const SharedPtr<XmlReader> &instanceDocument, SharedPtr<XmlSchemaSet> schemas)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| instanceDocument | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | XML スキーマを推測するための XML 文書を含む [XmlReader](../../../system.xml/xmlreader/) オブジェクト |
| schemas | [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaSet](../../xmlschemaset/)\> | 推測スキーマを洗練するために使用される既存のスキーマを含む [XmlSchemaSet](../../xmlschemaset/) オブジェクト |

### 戻り値

推測されたスキーマを含む [XmlSchemaSet](../../xmlschemaset/) オブジェクト。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [XmlSchemaSet](../../xmlschemaset/)
* クラス [XmlReader](../../../system.xml/xmlreader/)
* クラス [XmlSchemaInference](../)
* 名前空間 [System::Xml::Schema](../../)
* ライブラリ [Aspose.Slides](../../../)