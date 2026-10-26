---
title: Load()
second_title: Aspose.Slides C++ API 参考
description: 从指定的 URL 加载 XML 文档。
type: docs
weight: 508
url: /zh/system.xml/xmldocument/load/
---
## XmlDocument::Load(String) 方法

从指定的 URL 加载 XML 文档。

```cpp
virtual void System::Xml::XmlDocument::Load(String filename)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filename | [String](../../../system/string/) | 用于加载 XML 文档的文件的 URL。该 URL 可以是本地文件或 HTTP URL（[Web](../../../system.web/) 地址）。 |

## XmlDocument::Load(SharedPtr\<IO::Stream\>) 方法

从指定的流加载 XML 文档。

```cpp
virtual void System::Xml::XmlDocument::Load(SharedPtr<IO::Stream> inStream)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inStream | [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | 包含要加载的 XML 文档的流。 |

## XmlDocument::Load(SharedPtr\<IO::TextReader\>) 方法

从指定的 TextReader 加载 XML 文档。

```cpp
virtual void System::Xml::XmlDocument::Load(SharedPtr<IO::TextReader> txtReader)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| txtReader | [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\> | 用于向文档提供 XML 数据的 TextReader。 |

## XmlDocument::Load(SharedPtr\<XmlReader\>) 方法

从指定的 [XmlReader](../../xmlreader/) 加载 XML 文档。

```cpp
virtual void System::Xml::XmlDocument::Load(SharedPtr<XmlReader> reader)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| reader | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\> | 用于向文档提供 XML 数据的 [XmlReader](../../xmlreader/)。 |

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [String](../../../system/string/)
* 类 [XmlDocument](../)
* 类 [Stream](../../../system.io/stream/)
* 类 [TextReader](../../../system.io/textreader/)
* 类 [XmlReader](../../xmlreader/)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)