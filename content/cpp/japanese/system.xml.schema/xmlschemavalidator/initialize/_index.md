---
title: Initialize()
second_title: C++ 用 Aspose.Slides API リファレンス
description: XmlSchemaValidator オブジェクトの状態を初期化します。
type: docs
weight: 118
url: /ja/system.xml.schema/xmlschemavalidator/initialize/
---
## XmlSchemaValidator::Initialize() メソッド


[XmlSchemaValidator](../) オブジェクトの状態を初期化します。

```cpp
void System::Xml::Schema::XmlSchemaValidator::Initialize()
```


## XmlSchemaValidator::Initialize(const SharedPtr\<XmlSchemaObject\>\&) メソッド


部分検証用に指定された [XmlSchemaObject](../../xmlschemaobject/) を使用して、[XmlSchemaValidator](../) オブジェクトの状態を初期化します。

```cpp
void System::Xml::Schema::XmlSchemaValidator::Initialize(const SharedPtr<XmlSchemaObject> &partialValidationType)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| partialValidationType | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaObject](../../xmlschemaobject/)\>\& | [XmlSchemaElement](../../xmlschemaelement/)、[XmlSchemaAttribute](../../xmlschemaattribute/)、または[XmlSchemaType](../../xmlschematype/) オブジェクトで、部分検証のために [XmlSchemaValidator](../) オブジェクトの検証コンテキストを初期化します。 |

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [XmlSchemaValidator](../)
* クラス [XmlSchemaObject](../../xmlschemaobject/)
* 名前空間 [System::Xml::Schema](../../)
* ライブラリ [Aspose.Slides](../../../)