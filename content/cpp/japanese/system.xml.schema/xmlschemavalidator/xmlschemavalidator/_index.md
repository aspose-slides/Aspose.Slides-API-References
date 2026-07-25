---
title: XmlSchemaValidator()
second_title: Aspose.Slides for C++ API リファレンス
description: XmlSchemaValidator クラスの新しいインスタンスを初期化します。
type: docs
weight: 92
url: /ja/system.xml.schema/xmlschemavalidator/xmlschemavalidator/
---
## XmlSchemaValidator::XmlSchemaValidator(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlSchemaSet\>\&, const SharedPtr\<IXmlNamespaceResolver\>\&, XmlSchemaValidationFlags) コンストラクタ

新しい [XmlSchemaValidator](../) クラスのインスタンスを初期化します。

```cpp
System::Xml::Schema::XmlSchemaValidator::XmlSchemaValidator(const SharedPtr<XmlNameTable> &nameTable, const SharedPtr<XmlSchemaSet> &schemas, const SharedPtr<IXmlNamespaceResolver> &namespaceResolver, XmlSchemaValidationFlags validationFlags)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| nameTable | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../../system.xml/xmlnametable/)\>\& | 要素と属性名を原子化された文字列として含む [XmlNameTable](../../../system.xml/xmlnametable/) オブジェクト。 |
| schemas | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaSet](../../xmlschemaset/)\>\& | 検証に使用される XML [Schema](../../) 定義言語 (XSD) スキーマを含む [XmlSchemaSet](../../xmlschemaset/) オブジェクト。 |
| namespaceResolver | const [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\>\& | 検証中に遭遇した名前空間を解決するために使用される [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) オブジェクト。 |
| validationFlags | [XmlSchemaValidationFlags](../../xmlschemavalidationflags/) | スキーマ検証オプションを指定する XmlSchemaValidationFlags 値。 |

## 参照

* 列挙体 [XmlSchemaValidationFlags](../../xmlschemavalidationflags/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [XmlNameTable](../../../system.xml/xmlnametable/)
* クラス [XmlSchemaSet](../../xmlschemaset/)
* クラス [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* クラス [XmlSchemaValidator](../)
* 名前空間 [System::Xml::Schema](../../)
* ライブラリ [Aspose.Slides](../../../)