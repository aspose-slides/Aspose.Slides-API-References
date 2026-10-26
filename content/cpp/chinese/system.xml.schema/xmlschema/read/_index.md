---
title: Read()
second_title: Aspose.Slides for C++ API 参考
description: "从提供的 IO::TextReader 读取 XML 架构。"
type: docs
weight: 365
url: /zh/system.xml.schema/xmlschema/read/
---
## XmlSchema::Read(const SharedPtr\<IO::TextReader\>\&, ValidationEventHandler) 方法

从提供的[IO::TextReader](../../../system.io/textreader/)读取 XML [Schema](../../)。

```cpp
static SharedPtr<XmlSchema> System::Xml::Schema::XmlSchema::Read(const SharedPtr<IO::TextReader> &reader, ValidationEventHandler validationEventHandler)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | 包含待读取 XML [Schema](../../) 的 [IO::TextReader](../../../system.io/textreader/)。 |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | 接收有关 XML [Schema](../../) 语法错误信息的验证事件处理程序。 |

### 返回值

表示 XML [Schema](../../) 的 [XmlSchema](../) 对象。

## XmlSchema::Read(const SharedPtr\<IO::Stream\>\&, ValidationEventHandler) 方法

从提供的流读取 XML [Schema](../../)。

```cpp
static SharedPtr<XmlSchema> System::Xml::Schema::XmlSchema::Read(const SharedPtr<IO::Stream> &stream, ValidationEventHandler validationEventHandler)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | 提供的数据流。 |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | 接收有关 XML [Schema](../../) 语法错误信息的验证事件处理程序。 |

### 返回值

表示 XML [Schema](../../) 的 [XmlSchema](../) 对象。

## XmlSchema::Read(const SharedPtr\<XmlReader\>\&, ValidationEventHandler) 方法

从提供的[XmlReader](../../../system.xml/xmlreader/)读取 XML [Schema](../../)。

```cpp
static SharedPtr<XmlSchema> System::Xml::Schema::XmlSchema::Read(const SharedPtr<XmlReader> &reader, ValidationEventHandler validationEventHandler)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | 包含待读取 XML [Schema](../../) 的 [XmlReader](../../../system.xml/xmlreader/)。 |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | 接收有关 XML [Schema](../../) 语法错误信息的验证事件处理程序。 |

### 返回值

表示 XML [Schema](../../) 的 [XmlSchema](../) 对象。

## 另请参见

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ValidationEventHandler](../../validationeventhandler/)
* Class [XmlSchema](../)
* Class [TextReader](../../../system.io/textreader/)
* Class [Stream](../../../system.io/stream/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)