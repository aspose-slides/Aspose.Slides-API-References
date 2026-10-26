---
title: GetUnspecifiedDefaultAttributes()
second_title: Aspose.Slides for C++ API リファレンス
description: "要素コンテキストで XmlSchemaValidator::ValidateAttribute メソッドを使用して以前に検証されていないデフォルト値を持つ属性に対して、デフォルト属性の同一性制約を検証し、指定された List を XmlSchemaAttribute オブジェクトで入力します。"
type: docs
weight: 157
url: /ja/system.xml.schema/xmlschemavalidator/getunspecifieddefaultattributes/
---
## XmlSchemaValidator::GetUnspecifiedDefaultAttributes(const SharedPtr\<Collections::Generic::List\<SharedPtr\<Object\>\>\>\&) メソッド

デフォルト属性に対する同一性制約を検証し、要素コンテキストで [XmlSchemaValidator::ValidateAttribute](../validateattribute/) メソッドを使用して以前に検証されていないデフォルト値を持つ属性について、[XmlSchemaAttribute](../../xmlschemaattribute/) オブジェクトで List を入力します。

```cpp
void System::Xml::Schema::XmlSchemaValidator::GetUnspecifiedDefaultAttributes(const SharedPtr<Collections::Generic::List<SharedPtr<Object>>> &defaultAttributes)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| defaultAttributes | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::List](../../../system.collections.generic/list/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\>\>\& | 要素コンテキストでの検証中にまだ出会っていない属性について、[XmlSchemaAttribute](../../xmlschemaattribute/) オブジェクトで List を入力するためのリスト。 |

## 関連項目

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [List](../../../system.collections.generic/list/)
* クラス [Object](../../../system/object/)
* クラス [XmlSchemaValidator](../)
* 名前空間 [System::Xml::Schema](../../)
* ライブラリ [Aspose.Slides](../../../)