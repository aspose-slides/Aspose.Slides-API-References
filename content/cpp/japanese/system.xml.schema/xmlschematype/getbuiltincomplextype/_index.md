---
title: GetBuiltInComplexType()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された複合型の組み込み複合型を表す XmlSchemaComplexType を返します。
type: docs
weight: 196
url: /ja/system.xml.schema/xmlschematype/getbuiltincomplextype/
---
## XmlSchemaType::GetBuiltInComplexType(XmlTypeCode) メソッド

[XmlSchemaComplexType](../../xmlschemacomplextype/) を返します。これは、指定された複合型の組み込み複合型を表します。

```cpp
static SharedPtr<XmlSchemaComplexType> System::Xml::Schema::XmlSchemaType::GetBuiltInComplexType(XmlTypeCode typeCode)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| typeCode | [XmlTypeCode](../../xmltypecode/) | 複合型を表す XmlTypeCode の値のいずれか。 |

### 戻り値

組み込み複合型を表す [XmlSchemaComplexType](../../xmlschemacomplextype/)。

## XmlSchemaType::GetBuiltInComplexType(const SharedPtr\<XmlQualifiedName\>\&) メソッド

[XmlSchemaComplexType](../../xmlschemacomplextype/) を返します。これは、修飾名で指定された複合型の組み込み複合型を表します。

```cpp
static SharedPtr<XmlSchemaComplexType> System::Xml::Schema::XmlSchemaType::GetBuiltInComplexType(const SharedPtr<XmlQualifiedName> &qualifiedName)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| qualifiedName | const [SharedPtr](../../../system/sharedptr/)\<[XmlQualifiedName](../../../system.xml/xmlqualifiedname/)\>\& | 複合型の [XmlQualifiedName](../../../system.xml/xmlqualifiedname/)。 |

### 戻り値

組み込み複合型を表す [XmlSchemaComplexType](../../xmlschemacomplextype/)。

## 参照

* 列挙型 [XmlTypeCode](../../xmltypecode/)
* 型エイリアス [SharedPtr](../../../system/sharedptr/)
* クラス [XmlSchemaComplexType](../../xmlschemacomplextype/)
* クラス [XmlSchemaType](../)
* クラス [XmlQualifiedName](../../../system.xml/xmlqualifiedname/)
* 名前空間 [System::Xml::Schema](../../)
* ライブラリ [Aspose.Slides](../../../)