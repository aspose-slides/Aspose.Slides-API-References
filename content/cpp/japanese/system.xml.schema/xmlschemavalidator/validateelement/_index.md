---
title: ValidateElement()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のコンテキストで要素を検証します。
type: docs
weight: 131
url: /ja/system.xml.schema/xmlschemavalidator/validateelement/
---
## XmlSchemaValidator::ValidateElement(const String\&, const String\&, const SharedPtr\<XmlSchemaInfo\>\&) メソッド

現在のコンテキストで要素を検証します。

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateElement(const String &localName, const String &namespaceUri, const SharedPtr<XmlSchemaInfo> &schemaInfo)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | 検証対象要素のローカル名です。 |
| namespaceUri | const [String](../../../system/string/)\& | 検証対象要素の名前空間 URI です。 |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | 要素名の検証が成功したときにそのプロパティが設定される [XmlSchemaInfo](../../xmlschemainfo/) オブジェクトです。このパラメータは **nullptr** にすることができます。 |

## XmlSchemaValidator::ValidateElement(const String\&, const String\&, const SharedPtr\<XmlSchemaInfo\>\&, const String\&, const String\&, const String\&, const String\&) メソッド

現在のコンテキストで要素を検証し、**xsi:Type**、**xsi:Nil**、**xsi:SchemaLocation**、および **xsi:NoNamespaceSchemaLocation** 属性値が指定されている場合に検証します。

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateElement(const String &localName, const String &namespaceUri, const SharedPtr<XmlSchemaInfo> &schemaInfo, const String &xsiType, const String &xsiNil, const String &xsiSchemaLocation, const String &xsiNoNamespaceSchemaLocation)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | 検証対象要素のローカル名です。 |
| namespaceUri | const [String](../../../system/string/)\& | 検証対象要素の名前空間 URI です。 |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | 要素名の検証が成功したときにそのプロパティが設定される [XmlSchemaInfo](../../xmlschemainfo/) オブジェクトです。このパラメータは **nullptr** にすることができます。 |
| xsiType | const [String](../../../system/string/)\& | 要素の **xsi:Type** 属性値です。このパラメータは **nullptr** にすることができます。 |
| xsiNil | const [String](../../../system/string/)\& | 要素の **xsi:Nil** 属性値です。このパラメータは **nullptr** にすることができます。 |
| xsiSchemaLocation | const [String](../../../system/string/)\& | 要素の **xsi:SchemaLocation** 属性値です。このパラメータは **nullptr** にすることができます。 |
| xsiNoNamespaceSchemaLocation | const [String](../../../system/string/)\& | 要素の **xsi:NoNamespaceSchemaLocation** 属性値です。このパラメータは **nullptr** にすることができます。 |

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [String](../../../system/string/)
* クラス [XmlSchemaInfo](../../xmlschemainfo/)
* クラス [XmlSchemaValidator](../)
* 名前空間 [System::Xml::Schema](../../)
* ライブラリ [Aspose.Slides](../../../)