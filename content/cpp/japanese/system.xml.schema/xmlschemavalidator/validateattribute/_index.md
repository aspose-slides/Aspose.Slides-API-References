---
title: ValidateAttribute()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在の要素コンテキストで属性名、名前空間 URI、および値を検証します。
type: docs
weight: 144
url: /ja/system.xml.schema/xmlschemavalidator/validateattribute/
---
## XmlSchemaValidator::ValidateAttribute(const String&, const String&, const String&, const SharedPtr<XmlSchemaInfo>&) メソッド


現在の要素コンテキストで属性名、名前空間 URI、そして値を検証します。

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateAttribute(const String &localName, const String &namespaceUri, const String &attributeValue, const SharedPtr<XmlSchemaInfo> &schemaInfo)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| localName | const [String](../../../system/string/)& | 検証対象の属性のローカル名。 |
| namespaceUri | const [String](../../../system/string/)& | 検証対象の属性の名前空間 URI。 |
| attributeValue | const [String](../../../system/string/)& | 検証対象の属性の値。 |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)<[XmlSchemaInfo](../../xmlschemainfo/)>& | 属性の検証が成功した際にプロパティが設定される [XmlSchemaInfo](../../xmlschemainfo/) オブジェクト。このパラメータは **nullptr** にすることができます。 |

### 戻り値

検証された属性の値。

## XmlSchemaValidator::ValidateAttribute(const String&, const String&, XmlValueGetter, const SharedPtr<XmlSchemaInfo>&) メソッド


現在の要素コンテキストで属性名、名前空間 URI、そして値を検証します。

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateAttribute(const String &localName, const String &namespaceUri, XmlValueGetter attributeValue, const SharedPtr<XmlSchemaInfo> &schemaInfo)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| localName | const [String](../../../system/string/)& | 検証対象の属性のローカル名。 |
| namespaceUri | const [String](../../../system/string/)& | 検証対象の属性の名前空間 URI。 |
| attributeValue | [XmlValueGetter](../../xmlvaluegetter/) | 属性の値を XML [Schema](../../) 定義言語 (XSD) の属性タイプと互換性のある型として渡すために使用される XmlValueGetter コールバック。 |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)<[XmlSchemaInfo](../../xmlschemainfo/)>& | 属性の検証が成功した際にプロパティが設定される [XmlSchemaInfo](../../xmlschemainfo/) オブジェクト。このパラメータは **nullptr** にできます。 |

### 戻り値

検証された属性の値。

## 関連項目

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [XmlValueGetter](../../xmlvaluegetter/)
* クラス [Object](../../../system/object/)
* クラス [String](../../../system/string/)
* クラス [XmlSchemaInfo](../../xmlschemainfo/)
* クラス [XmlSchemaValidator](../)
* 名前空間 [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)