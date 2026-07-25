---
title: XPathDocument()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された XmlReader オブジェクトに含まれる XML データから XPathDocument クラスの新しいインスタンスを初期化します。
type: docs
weight: 1
url: /ja/system.xml.xpath/xpathdocument/xpathdocument/
---
## XPathDocument::XPathDocument(const SharedPtr\<XmlReader\>\&) コンストラクター

指定された [XmlReader](../../../system.xml/xmlreader/) オブジェクトに含まれる XML データから [XPathDocument](../) クラスの新しいインスタンスを初期化します。

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const SharedPtr<XmlReader> &reader)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | [XmlReader](../../../system.xml/xmlreader/) オブジェクトは XML データを含んでいます。 |

## XPathDocument::XPathDocument(const SharedPtr\<XmlReader\>\&, XmlSpace) コンストラクター

指定された [XmlReader](../../../system.xml/xmlreader/) オブジェクトに含まれる XML データと、指定された空白処理を使用して、[XPathDocument](../) クラスの新しいインスタンスを初期化します。

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const SharedPtr<XmlReader> &reader, XmlSpace space)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | [XmlReader](../../../system.xml/xmlreader/) オブジェクトは XML データを含んでいます。 |
| space | [XmlSpace](../../../system.xml/xmlspace/) | XmlSpace オブジェクトです。 |

## XPathDocument::XPathDocument(const SharedPtr\<IO::TextReader\>\&) コンストラクター

指定された TextReader オブジェクトに含まれる XML データから [XPathDocument](../) クラスの新しいインスタンスを初期化します。

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const SharedPtr<IO::TextReader> &textReader)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| textReader | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | TextReader オブジェクトは XML データを含んでいます。 |

## XPathDocument::XPathDocument(const SharedPtr\<IO::Stream\>\&) コンストラクター

指定された Stream オブジェクトの XML データから [XPathDocument](../) クラスの新しいインスタンスを初期化します。

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const SharedPtr<IO::Stream> &stream)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Stream オブジェクトは XML データを含んでいます。 |

## XPathDocument::XPathDocument(const String\&) コンストラクター

指定されたファイルの XML データから [XPathDocument](../) クラスの新しいインスタンスを初期化します。

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const String &uri)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| uri | const [String](../../../system/string/)\& | XML データを含むファイルのパスです。 |

## XPathDocument::XPathDocument(const String\&, XmlSpace) コンストラクター

指定された空白処理で指定されたファイルの XML データから [XPathDocument](../) クラスの新しいインスタンスを初期化します。

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const String &uri, XmlSpace space)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| uri | const [String](../../../system/string/)\& | XML データを含むファイルのパスです。 |
| space | [XmlSpace](../../../system.xml/xmlspace/) | XmlSpace オブジェクトです。 |

## 参照

* Enum [XmlSpace](../../../system.xml/xmlspace/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XPathDocument](../)
* Class [TextReader](../../../system.io/textreader/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)