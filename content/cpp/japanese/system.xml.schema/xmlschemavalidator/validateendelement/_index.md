---
title: ValidateEndElement()
second_title: Aspose.Slides for C++ API リファレンス
description: 単純コンテンツを持つ要素については、そのデータ型に従って要素のテキスト内容が有効かどうかを検証し、複合コンテンツを持つ要素については、現在の要素の内容が完全であるかどうかを検証します。
type: docs
weight: 209
url: /ja/system.xml.schema/xmlschemavalidator/validateendelement/
---
## XmlSchemaValidator::ValidateEndElement(const SharedPtr\<XmlSchemaInfo\>\&) method


単純コンテンツを持つ要素については、そのデータ型に従って要素のテキスト内容が有効かどうかを検証し、複合コンテンツを持つ要素については、現在の要素の内容が完全であるかどうかを検証します。

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateEndElement(const SharedPtr<XmlSchemaInfo> &schemaInfo)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | [XmlSchemaInfo](../../xmlschemainfo/) オブジェクトで、要素の検証が成功した際にそのプロパティが設定されます。このパラメータは **nullptr** にすることができます。 |

### 戻り値

要素が単純コンテンツを持つ場合の、解析された型付きテキスト値を返します。

## XmlSchemaValidator::ValidateEndElement(const SharedPtr\<XmlSchemaInfo\>\&, const SharedPtr\<Object\>\&) method


指定された要素のテキスト内容が、データ型に従って有効かどうかを検証します。

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateEndElement(const SharedPtr<XmlSchemaInfo> &schemaInfo, const SharedPtr<Object> &typedValue)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | [XmlSchemaInfo](../../xmlschemainfo/) オブジェクトで、要素のテキスト内容の検証が成功した際にそのプロパティが設定されます。このパラメータは **nullptr** にすることができます。 |
| typedValue | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | 要素の型付きテキスト内容です。 |

### 戻り値

要素の解析された型付き単純コンテンツを返します。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [Object](../../../system/object/)
* クラス [XmlSchemaInfo](../../xmlschemainfo/)
* クラス [XmlSchemaValidator](../)
* 名前空間 [System::Xml::Schema](../../)
* ライブラリ [Aspose.Slides](../../../)