---
title: ChangeType()
second_title: Aspose.Slides for C++ API リファレンス
description: XmlSchemaDatatype が表す XML スキーマ型の有効な表現のいずれかの型である指定された値を、指定された実行時型に変換します。
type: docs
weight: 66
url: /ja/system.xml.schema/xmlschemadatatype/changetype/
---
## XmlSchemaDatatype::ChangeType(SharedPtr\<Object\>, const TypeInfo\&) メソッド

指定された値を、[XmlSchemaDatatype](../) が表す XML スキーマ型の有効な表現のいずれかの型から、指定された実行時型に変換します。

```cpp
virtual SharedPtr<Object> System::Xml::Schema::XmlSchemaDatatype::ChangeType(SharedPtr<Object> value, const TypeInfo &targetType)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 指定された型に変換する入力値です。 |
| targetType | const [TypeInfo](../../../system/typeinfo/)\& | 入力値を変換する対象の型です。 |

### 戻り値

変換された入力値です。

## XmlSchemaDatatype::ChangeType(SharedPtr\<Object\>, const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) メソッド

指定された値を、[XmlSchemaDatatype](../) が表す XML スキーマ型の有効な表現のいずれかの型から、[XmlSchemaDatatype](../) が **xs:QName** 型またはその派生型を表す場合に [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) を使用して、指定された実行時型に変換します。

```cpp
virtual SharedPtr<Object> System::Xml::Schema::XmlSchemaDatatype::ChangeType(SharedPtr<Object> value, const TypeInfo &targetType, SharedPtr<IXmlNamespaceResolver> namespaceResolver)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 指定された型に変換する入力値です。 |
| targetType | const [TypeInfo](../../../system/typeinfo/)\& | 入力値を変換する対象の型です。 |
| namespaceResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | 名前空間プレフィックスの解決に使用される [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) です。これは [XmlSchemaDatatype](../) が **xs:QName** 型またはその派生型を表す場合にのみ有用です。 |

### 戻り値

変換された入力値です。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [Object](../../../system/object/)
* クラス [TypeInfo](../../../system/typeinfo/)
* クラス [XmlSchemaDatatype](../)
* クラス [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* 名前空間 [System::Xml::Schema](../../)
* ライブラリ [Aspose.Slides](../../../)