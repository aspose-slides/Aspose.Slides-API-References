---
title: IsDerivedFrom()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された派生スキーマ型が、指定された基本スキーマ型から派生しているかどうかを示す値を返します。
type: docs
weight: 209
url: /ja/system.xml.schema/xmlschematype/isderivedfrom/
---
## XmlSchemaType::IsDerivedFrom(SharedPtr\<XmlSchemaType\>, const SharedPtr\<XmlSchemaType\>\&, XmlSchemaDerivationMethod) メソッド

指定された派生スキーマ型が、指定された基本スキーマ型から派生しているかどうかを示す値を返します。

```cpp
static bool System::Xml::Schema::XmlSchemaType::IsDerivedFrom(SharedPtr<XmlSchemaType> derivedType, const SharedPtr<XmlSchemaType> &baseType, XmlSchemaDerivationMethod except)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| derivedType | [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaType](../)\> | テスト対象の派生[XmlSchemaType](../)。 |
| baseType | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaType](../)\>\& | 派生[XmlSchemaType](../)をテストするための基本[XmlSchemaType](../)。 |
| except | [XmlSchemaDerivationMethod](../../xmlschemaderivationmethod/) | テストから除外する型派生方法を表す XmlSchemaDerivationMethod の値のいずれかです。 |

### 戻り値

**true** は、派生型が基本型から派生している場合です。そうでない場合は **false** です。

## 参照

* Enum [XmlSchemaDerivationMethod](../../xmlschemaderivationmethod/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchemaType](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)