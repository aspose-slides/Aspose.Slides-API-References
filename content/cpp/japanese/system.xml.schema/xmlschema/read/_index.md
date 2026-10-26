---
title: Read()
second_title: Aspose.Slides for C++ API リファレンス
description: "提供された IO::TextReader から XML スキーマを読み取ります。"
type: docs
weight: 365
url: /ja/system.xml.schema/xmlschema/read/
---
## XmlSchema::Read(const SharedPtr\<IO::TextReader\>\&, ValidationEventHandler) method

提供された[IO::TextReader](../../../system.io/textreader/)からXML [Schema](../../)を読み取ります。

```cpp
static SharedPtr<XmlSchema> System::Xml::Schema::XmlSchema::Read(const SharedPtr<IO::TextReader> &reader, ValidationEventHandler validationEventHandler)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | [IO::TextReader](../../../system.io/textreader/)は、読み込むXML [Schema](../../)を含みます。 |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | XML [Schema](../../)構文エラーに関する情報を受け取る検証イベントハンドラ。 |

### 戻り値

XML [Schema](../../)を表す[XmlSchema](../)オブジェクト。

## XmlSchema::Read(const SharedPtr\<IO::Stream\>\&, ValidationEventHandler) method

提供されたストリームからXML [Schema](../../)を読み取ります。

```cpp
static SharedPtr<XmlSchema> System::Xml::Schema::XmlSchema::Read(const SharedPtr<IO::Stream> &stream, ValidationEventHandler validationEventHandler)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | 提供されたデータストリーム。 |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | XML [Schema](../../)構文エラーに関する情報を受け取る検証イベントハンドラ。 |

### 戻り値

XML [Schema](../../)を表す[XmlSchema](../)オブジェクト。

## XmlSchema::Read(const SharedPtr\<XmlReader\>\&, ValidationEventHandler) method

提供された[XmlReader](../../../system.xml/xmlreader/)からXML [Schema](../../)を読み取ります。

```cpp
static SharedPtr<XmlSchema> System::Xml::Schema::XmlSchema::Read(const SharedPtr<XmlReader> &reader, ValidationEventHandler validationEventHandler)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | [XmlReader](../../../system.xml/xmlreader/)は、読み込むXML [Schema](../../)を含みます。 |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | XML [Schema](../../)構文エラーに関する情報を受け取る検証イベントハンドラ。 |

### 戻り値

XML [Schema](../../)を表す[XmlSchema](../)オブジェクト。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* 型定義 [ValidationEventHandler](../../validationeventhandler/)
* クラス [XmlSchema](../)
* クラス [TextReader](../../../system.io/textreader/)
* クラス [Stream](../../../system.io/stream/)
* クラス [XmlReader](../../../system.xml/xmlreader/)
* 名前空間 [System::Xml::Schema](../../)
* ライブラリ [Aspose.Slides](../../../)