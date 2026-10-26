---
title: Write()
second_title: Aspose.Slides for C++ APIリファレンス
description: 提供されたデータストリームに XML スキーマを書き込みます。
type: docs
weight: 339
url: /ja/system.xml.schema/xmlschema/write/
---
## XmlSchema::Write(const SharedPtr\<IO::Stream\>\&) メソッド

Provides the XML [Schema](../../) to the supplied data stream.

```cpp
void System::Xml::Schema::XmlSchema::Write(const SharedPtr<IO::Stream> &stream)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | 提供されたデータストリーム。 |

## XmlSchema::Write(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlNamespaceManager\>\&) メソッド

指定された [XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/) を使用して、提供されたストリームに XML [Schema](../../) を書き込みます。

```cpp
void System::Xml::Schema::XmlSchema::Write(const SharedPtr<IO::Stream> &stream, const SharedPtr<XmlNamespaceManager> &namespaceManager)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | 提供されたデータストリーム。 |
| namespaceManager | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/)\>\& | [XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/)。 |

## XmlSchema::Write(const SharedPtr\<IO::TextWriter\>\&) メソッド

提供された [IO::TextWriter](../../../system.io/textwriter/) に XML [Schema](../../) を書き込みます。

```cpp
void System::Xml::Schema::XmlSchema::Write(const SharedPtr<IO::TextWriter> &writer)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| writer | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | 書き込む対象の [IO::TextWriter](../../../system.io/textwriter/)。 |

## XmlSchema::Write(const SharedPtr\<IO::TextWriter\>\&, const SharedPtr\<XmlNamespaceManager\>\&) メソッド

提供された TextWriter に XML [Schema](../../) を書き込みます。

```cpp
void System::Xml::Schema::XmlSchema::Write(const SharedPtr<IO::TextWriter> &writer, const SharedPtr<XmlNamespaceManager> &namespaceManager)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| writer | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | 書き込む対象の [IO::TextWriter](../../../system.io/textwriter/)。 |
| namespaceManager | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/)\>\& | [XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/)。 |

## XmlSchema::Write(const SharedPtr\<XmlWriter\>\&) メソッド

提供された [XmlWriter](../../../system.xml/xmlwriter/) に XML [Schema](../../) を書き込みます。

```cpp
void System::Xml::Schema::XmlSchema::Write(const SharedPtr<XmlWriter> &writer)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| writer | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | 書き込む対象の [XmlWriter](../../../system.xml/xmlwriter/)。 |

## XmlSchema::Write(const SharedPtr\<XmlWriter\>\&, const SharedPtr\<XmlNamespaceManager\>\&) メソッド

提供された [XmlWriter](../../../system.xml/xmlwriter/) に XML [Schema](../../) を書き込みます。

```cpp
void System::Xml::Schema::XmlSchema::Write(const SharedPtr<XmlWriter> &writer, const SharedPtr<XmlNamespaceManager> &namespaceManager)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| writer | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | 書き込む対象の [XmlWriter](../../../system.xml/xmlwriter/)。 |
| namespaceManager | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/)\>\& | [XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/)。 |

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [Stream](../../../system.io/stream/)
* クラス [XmlSchema](../)
* クラス [XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/)
* クラス [TextWriter](../../../system.io/textwriter/)
* クラス [XmlWriter](../../../system.xml/xmlwriter/)
* 名前空間 [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)