---
title: Validate()
second_title: Aspose.Slides for C++ API リファレンス
description: "XmlDocument を、XmlDocument::get_Schemas リストに含まれる XML スキーマ定義言語 (XSD) スキーマに対して検証します。"
type: docs
weight: 573
url: /ja/system.xml/xmldocument/validate/
---
## XmlDocument::Validate(Schema::ValidationEventHandler) メソッド

[XmlDocument](../) を、[XmlDocument::get_Schemas](../get_schemas/) リストに含まれる XML [Schema](../../../system.xml.schema/) Definition Language (XSD) スキーマに対して検証します。

```cpp
void System::Xml::XmlDocument::Validate(Schema::ValidationEventHandler validationEventHandler)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| validationEventHandler | [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) | [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) は、スキーマ検証の警告とエラーに関する情報を受け取るオブジェクトです。 |

## XmlDocument::Validate(Schema::ValidationEventHandler, const SharedPtr\<XmlNode\>\&) メソッド

[XmlNode](../../xmlnode/) オブジェクトを、[XmlDocument::get_Schemas](../get_schemas/) リスト内の XML [Schema](../../../system.xml.schema/) Definition Language (XSD) スキーマに対して検証します。

```cpp
void System::Xml::XmlDocument::Validate(Schema::ValidationEventHandler validationEventHandler, const SharedPtr<XmlNode> &nodeToValidate)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| validationEventHandler | [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) | [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) は、スキーマ検証の警告とエラーに関する情報を受け取るオブジェクトです。 |
| nodeToValidate | const [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\>\& | [XmlNode](../../xmlnode/) は、検証するために [XmlDocument](../) から作成されたオブジェクトです。 |

## 参照

* 型定義 [ValidationEventHandler](../../../system.xml.schema/validationeventhandler/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [XmlDocument](../)
* クラス [XmlNode](../../xmlnode/)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)