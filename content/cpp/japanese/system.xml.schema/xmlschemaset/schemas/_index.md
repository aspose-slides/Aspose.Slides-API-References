---
title: Schemas()
second_title: Aspose.Slides for C++ API リファレンス
description: XmlSchemaSet に含まれるすべての XML スキーマ定義言語 (XSD) スキーマのコレクションを返します。
type: docs
weight: 248
url: /ja/system.xml.schema/xmlschemaset/schemas/
---
## XmlSchemaSet::Schemas() メソッド


[XmlSchemaSet](../) に含まれるすべての XML [Schema](../../) 定義言語 (XSD) スキーマのコレクションを返します。

```cpp
SharedPtr<Collections::Generic::IList<SharedPtr<XmlSchema>>> System::Xml::Schema::XmlSchemaSet::Schemas()
```


### 戻り値

[XmlSchemaSet](../) に追加されたすべてのスキーマを含む IList オブジェクトです。[XmlSchemaSet](../) にスキーマが追加されていない場合、空のコレクションが返されます。

## XmlSchemaSet::Schemas(String) メソッド


[XmlSchemaSet](../) に含まれ、指定された名前空間に属するすべての XML [Schema](../../) 定義言語 (XSD) スキーマのコレクションを返します。

```cpp
SharedPtr<Collections::Generic::List<SharedPtr<XmlSchema>>> System::Xml::Schema::XmlSchemaSet::Schemas(String targetNamespace)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| targetNamespace | [String](../../../system/string/) | スキーマの **targetNamespace** プロパティ。 |

### 戻り値

[XmlSchemaSet](../) に追加された、指定された名前空間に属するすべてのスキーマを含む IList オブジェクトです。[XmlSchemaSet](../) にスキーマが追加されていない場合、空のコレクションが返されます。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IList](../../../system.collections.generic/ilist/)
* クラス [XmlSchema](../../xmlschema/)
* クラス [XmlSchemaSet](../)
* クラス [List](../../../system.collections.generic/list/)
* クラス [String](../../../system/string/)
* 名前空間 [System::Xml::Schema](../../)
* ライブラリ [Aspose.Slides](../../../)