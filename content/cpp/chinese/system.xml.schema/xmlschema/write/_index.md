---
title: Write()
second_title: Aspose.Slides C++ API 参考
description: 将 XML Schema 写入提供的数据流。
type: docs
weight: 339
url: /zh/system.xml.schema/xmlschema/write/
---
## XmlSchema::Write(const SharedPtr\<IO::Stream\>\&) method

将 XML [Schema](../../) 写入提供的数据流。

```cpp
void System::Xml::Schema::XmlSchema::Write(const SharedPtr<IO::Stream> &stream)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | 提供的数据流。 |

## XmlSchema::Write(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlNamespaceManager\>\&) method

使用指定的 [XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/) 将 XML [Schema](../../) 写入提供的 Stream。

```cpp
void System::Xml::Schema::XmlSchema::Write(const SharedPtr<IO::Stream> &stream, const SharedPtr<XmlNamespaceManager> &namespaceManager)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | 提供的数据流。 |
| namespaceManager | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/)\>\& | 提供的 [XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/)。 |

## XmlSchema::Write(const SharedPtr\<IO::TextWriter\>\&) method

将 XML [Schema](../../) 写入提供的 [IO::TextWriter](../../../system.io/textwriter/)。

```cpp
void System::Xml::Schema::XmlSchema::Write(const SharedPtr<IO::TextWriter> &writer)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| writer | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | 要写入的 [IO::TextWriter](../../../system.io/textwriter/)。 |

## XmlSchema::Write(const SharedPtr\<IO::TextWriter\>\&, const SharedPtr\<XmlNamespaceManager\>\&) method

将 XML [Schema](../../) 写入提供的 TextWriter。

```cpp
void System::Xml::Schema::XmlSchema::Write(const SharedPtr<IO::TextWriter> &writer, const SharedPtr<XmlNamespaceManager> &namespaceManager)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| writer | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | 要写入的 [IO::TextWriter](../../../system.io/textwriter/)。 |
| namespaceManager | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/)\>\& | 提供的 [XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/)。 |

## XmlSchema::Write(const SharedPtr\<XmlWriter\>\&) method

将 XML [Schema](../../) 写入提供的 [XmlWriter](../../../system.xml/xmlwriter/)。

```cpp
void System::Xml::Schema::XmlSchema::Write(const SharedPtr<XmlWriter> &writer)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| writer | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | 要写入的 [XmlWriter](../../../system.xml/xmlwriter/)。 |

## XmlSchema::Write(const SharedPtr\<XmlWriter\>\&, const SharedPtr\<XmlNamespaceManager\>\&) method

将 XML [Schema](../../) 写入提供的 [XmlWriter](../../../system.xml/xmlwriter/)。

```cpp
void System::Xml::Schema::XmlSchema::Write(const SharedPtr<XmlWriter> &writer, const SharedPtr<XmlNamespaceManager> &namespaceManager)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| writer | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | 要写入的 [XmlWriter](../../../system.xml/xmlwriter/)。 |
| namespaceManager | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/)\>\& | 提供的 [XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/)。 |

## 另请参见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [Stream](../../../system.io/stream/)
* 类 [XmlSchema](../)
* 类 [XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/)
* 类 [TextWriter](../../../system.io/textwriter/)
* 类 [XmlWriter](../../../system.xml/xmlwriter/)
* 命名空间 [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)