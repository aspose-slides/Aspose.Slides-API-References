---
title: get_SchemaInfo()
second_title: Aspose.Slides for C++ API リファレンス
description: スキーマ検証の結果として現在のノードに割り当てられたスキーマ情報を返します。
type: docs
weight: 196
url: /ja/system.xml/xmlreader/get_schemainfo/
---
## XmlReader::get_SchemaInfo() メソッド

現在のノードにスキーマ検証の結果として割り当てられたスキーマ情報を返します。

```cpp
virtual SharedPtr<Schema::IXmlSchemaInfo> System::Xml::XmlReader::get_SchemaInfo()
```

### 戻り値

現在のノードのスキーマ情報を含む IXmlSchemaInfo オブジェクトです。[Schema](../../../system.xml.schema/) 情報は要素、属性、または null でない [XmlReader::get_ValueType](../get_valuetype/) 値を持つテキストノードに設定できます。現在のノードが上記のタイプのいずれでもない場合、または [XmlReader](../) インスタンスがスキーマ情報を報告しない場合、このメソッドは **nullptr** を返します。このメソッドが [XmlTextReader](../../xmltextreader/) または [XmlValidatingReader](../../xmlvalidatingreader/) オブジェクトから呼び出された場合、このメソッドは常に **nullptr** を返します。これらの [XmlReader](../) 実装は get_SchemaInfo メソッドを介してスキーマ情報を公開しません。

## 参照

* typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IXmlSchemaInfo](../../../system.xml.schema/ixmlschemainfo/)
* クラス [XmlReader](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)