---
title: GetBuiltInSimpleType()
second_title: Aspose.Slides for C++ API リファレンス
description: 修飾名で指定された単純型の組み込み単純型を表す XmlSchemaSimpleType を返します。
type: docs
weight: 183
url: /ja/system.xml.schema/xmlschematype/getbuiltinsimpletype/
---
## XmlSchemaType::GetBuiltInSimpleType(const SharedPtr\<XmlQualifiedName\>\&) メソッド


指定された修飾名により指定された単純型の組み込み単純型を表す[XmlSchemaSimpleType](../../xmlschemasimpletype/)を返します。

```cpp
static SharedPtr<XmlSchemaSimpleType> System::Xml::Schema::XmlSchemaType::GetBuiltInSimpleType(const SharedPtr<XmlQualifiedName> &qualifiedName)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| qualifiedName | const [SharedPtr](../../../system/sharedptr/)\<[XmlQualifiedName](../../../system.xml/xmlqualifiedname/)\>\& | 単純型の[XmlQualifiedName](../../../system.xml/xmlqualifiedname/) |
 
### 戻り値

組み込み単純型を表す[XmlSchemaSimpleType](../../xmlschemasimpletype/)

## XmlSchemaType::GetBuiltInSimpleType(XmlTypeCode) メソッド


指定された単純型の組み込み単純型を表す[XmlSchemaSimpleType](../../xmlschemasimpletype/)を返します。

```cpp
static SharedPtr<XmlSchemaSimpleType> System::Xml::Schema::XmlSchemaType::GetBuiltInSimpleType(XmlTypeCode typeCode)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| typeCode | [XmlTypeCode](../../xmltypecode/) | 単純型を表す XmlTypeCode の値の1つ |
 
### 戻り値

組み込み単純型を表す[XmlSchemaSimpleType](../../xmlschemasimpletype/)

## 参照

* 列挙体 [XmlTypeCode](../../xmltypecode/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [XmlSchemaSimpleType](../../xmlschemasimpletype/)
* クラス [XmlQualifiedName](../../../system.xml/xmlqualifiedname/)
* クラス [XmlSchemaType](../)
* 名前空間 [System::Xml::Schema](../../)
* ライブラリ [Aspose.Slides](../../../)