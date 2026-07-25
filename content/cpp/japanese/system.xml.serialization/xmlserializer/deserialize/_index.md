---
title: Deserialize()
second_title: Aspose.Slides for C++ API リファレンス
description: XML ドキュメントをオブジェクトにデシリアライズします。
type: docs
weight: 14
url: /ja/system.xml.serialization/xmlserializer/deserialize/
---
## XmlSerializer::Deserialize(System::SharedPtr\<IO::Stream\>) メソッド

XML ドキュメントをオブジェクトにデシリアライズします。

```cpp
System::SharedPtr<Object> System::Xml::Serialization::XmlSerializer::Deserialize(System::SharedPtr<IO::Stream> stream)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | ドキュメントを読み取るためのストリーム。 |

### 戻り値

[Object](../../../system/object/) は、以前にドキュメントにシリアライズされたものです。

## XmlSerializer::Deserialize(System::SharedPtr\<IO::TextReader\>) メソッド

XML ドキュメントをオブジェクトにデシリアライズします。

```cpp
System::SharedPtr<Object> System::Xml::Serialization::XmlSerializer::Deserialize(System::SharedPtr<IO::TextReader> textReader)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| textReader | [System::SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\> | ドキュメントを読み取るためのリーダー。 |

### 戻り値

[Object](../../../system/object/) は、以前にドキュメントにシリアライズされたものです。

## XmlSerializer::Deserialize(System::SharedPtr\<XmlReader\>) メソッド

XML ドキュメントをオブジェクトにデシリアライズします。

```cpp
System::SharedPtr<Object> System::Xml::Serialization::XmlSerializer::Deserialize(System::SharedPtr<XmlReader> xmlReader)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| xmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | ドキュメントを読み取るためのリーダー。 |

### 戻り値

[Object](../../../system/object/) は、以前にドキュメントにシリアライズされたものです。

## XmlSerializer::Deserialize(System::SharedPtr\<XmlReader\>, String) メソッド

XML ドキュメントをオブジェクトにデシリアライズします。

```cpp
System::SharedPtr<Object> System::Xml::Serialization::XmlSerializer::Deserialize(System::SharedPtr<XmlReader> xmlReader, String encodingStyle)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| xmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | ドキュメントを読み取るためのリーダー。 |
| encodingStyle | [String](../../../system/string/) | オブジェクトをシリアライズする際に使用されるスタイル。 |

### 戻り値

[Object](../../../system/object/) は、以前にドキュメントにシリアライズされたものです。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [Object](../../../system/object/)
* クラス [Stream](../../../system.io/stream/)
* クラス [XmlSerializer](../)
* クラス [TextReader](../../../system.io/textreader/)
* クラス [XmlReader](../../../system.xml/xmlreader/)
* クラス [String](../../../system/string/)
* 名前空間 [System::Xml::Serialization](../../)
* ライブラリ [Aspose.Slides](../../../)