---
title: get_SchemaType()
second_title: Aspose.Slides for C++ API リファレンス
description: スキーマ型オブジェクトを返します。
type: docs
weight: 287
url: /ja/system.xml/xmlvalidatingreader/get_schematype/
---
## XmlValidatingReader::get_SchemaType() メソッド


スキーマ型オブジェクトを返します。

```cpp
SharedPtr<Object> System::Xml::XmlValidatingReader::get_SchemaType()
```


### 戻り値

ノードの値が組み込みの XML [Schema](../../../system.xml.schema/) 定義言語 (XSD) 型であるか、ユーザー定義の simpleType または complexType であるかに応じて、XmlSchemaDatatype、XmlSchemaSimpleType、または XmlSchemaComplexType が返されます。現在のノードにスキーマ型がない場合は **nullptr** 。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [Object](../../../system/object/)
* クラス [XmlValidatingReader](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)