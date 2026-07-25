---
title: Add()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された URL に位置するスキーマをスキーマコレクションに追加します。
type: docs
weight: 40
url: /ja/system.xml.schema/xmlschemacollection/add/
---
## XmlSchemaCollection::Add(const String\&, const String\&) メソッド


指定された URL に位置するスキーマをスキーマコレクションに追加します。

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const String &ns, const String &uri)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | スキーマに関連付けられた名前空間 URI。XML スキーマの場合、通常は **targetNamespace** です。 |
| uri | const [String](../../../system/string/)\& | ロードするスキーマを指定する URL。 |

### 戻り値

[XmlSchema](../../xmlschema/) がスキーマコレクションに追加されます。追加されるスキーマが XDR スキーマである場合、またはスキーマにコンパイルエラーがある場合は **nullptr** です。

## XmlSchemaCollection::Add(const String\&, const SharedPtr\<XmlReader\>\&) メソッド


[XmlReader](../../../system.xml/xmlreader/) に含まれるスキーマをスキーマコレクションに追加します。

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const String &ns, const SharedPtr<XmlReader> &reader)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | スキーマに関連付けられた名前空間 URI。XML スキーマの場合、通常は **targetNamespace** です。 |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | 追加するスキーマを含む [XmlReader](../../../system.xml/xmlreader/)。 |

### 戻り値

[XmlSchema](../../xmlschema/) がスキーマコレクションに追加されます。追加されるスキーマが XDR スキーマである場合、またはスキーマにコンパイルエラーがある場合は **nullptr** です。

## XmlSchemaCollection::Add(const String\&, const SharedPtr\<XmlReader\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) メソッド


[XmlReader](../../../system.xml/xmlreader/) に含まれるスキーマをスキーマコレクションに追加します。指定された [XmlResolver](../../../system.xml/xmlresolver/) は外部リソースの解決に使用されます。

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const String &ns, const SharedPtr<XmlReader> &reader, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | スキーマに関連付けられた名前空間 URI。XML スキーマの場合、通常は **targetNamespace** です。 |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | 追加するスキーマを含む [XmlReader](../../../system.xml/xmlreader/)。 |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) は **include** および **import** 要素、または **x-schema** 属性で参照される名前空間を解決するために使用されます (XDR スキーマ)。この値が **nullptr** の場合、外部参照は解決されません。 |

### 戻り値

[XmlSchema](../../xmlschema/) がスキーマコレクションに追加されます。追加されるスキーマが XDR スキーマである場合、またはスキーマにコンパイルエラーがある場合は **nullptr** です。

## XmlSchemaCollection::Add(const SharedPtr\<XmlSchema\>\&) メソッド


[XmlSchema](../../xmlschema/) をコレクションに追加します。

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const SharedPtr<XmlSchema> &schema)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | コレクションに追加する [XmlSchema](../../xmlschema/)。 |

### 戻り値

[XmlSchema](../../xmlschema/) オブジェクト。

## XmlSchemaCollection::Add(const SharedPtr\<XmlSchema\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) メソッド


[XmlSchema](../../xmlschema/) をコレクションに追加します。指定された [XmlResolver](../../../system.xml/xmlresolver/) は外部参照の解決に使用されます。

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const SharedPtr<XmlSchema> &schema, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | コレクションに追加する [XmlSchema](../../xmlschema/)。 |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) は **include** および **import** 要素で参照される名前空間を解決するために使用されます。 この値が **nullptr** の場合、外部参照は解決されません。 |

### 戻り値

[XmlSchema](../../xmlschema/) がスキーマコレクションに追加されます。

## XmlSchemaCollection::Add(const SharedPtr\<XmlSchemaCollection\>\&) メソッド


指定されたコレクションで定義されたすべての名前空間（関連付けられたスキーマを含む）をこのコレクションに追加します。

```cpp
void System::Xml::Schema::XmlSchemaCollection::Add(const SharedPtr<XmlSchemaCollection> &schema)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaCollection](../)\>\& | このコレクションに追加したい [XmlSchemaCollection](../)。 |

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [XmlSchema](../../xmlschema/)
* クラス [String](../../../system/string/)
* クラス [XmlSchemaCollection](../)
* クラス [XmlReader](../../../system.xml/xmlreader/)
* クラス [XmlResolver](../../../system.xml/xmlresolver/)
* 名前空間 [System::Xml::Schema](../../)
* ライブラリ [Aspose.Slides](../../../)