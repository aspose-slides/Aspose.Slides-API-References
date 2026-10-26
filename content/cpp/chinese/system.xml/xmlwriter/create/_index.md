---
title: Create()
second_title: Aspose.Slides for C++ API 参考
description: 使用指定的文件名创建一个新的 XmlWriter 实例。
type: docs
weight: 469
url: /zh/system.xml/xmlwriter/create/
---
## XmlWriter::Create(const String\&) 方法

使用指定的文件名创建一个新的 [XmlWriter](../) 实例。

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const String &outputFileName)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputFileName | const [String](../../../system/string/)\& | 您想写入的文件。[XmlWriter](../) 在指定路径创建文件并以 XML 1.0 文本语法写入。**outputFileName** 必须是文件系统路径。 |

### 返回值

一个 [XmlWriter](../) 对象。

## XmlWriter::Create(const String\&, SharedPtr\<XmlWriterSettings\>) 方法

使用文件名和 [XmlWriterSettings](../../xmlwritersettings/) 对象创建一个新的 [XmlWriter](../) 实例。

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const String &outputFileName, SharedPtr<XmlWriterSettings> settings)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputFileName | const [String](../../../system/string/)\& | 您想写入的文件。[XmlWriter](../) 在指定路径创建文件并以 XML 1.0 文本语法写入。**outputFileName** 必须是文件系统路径。 |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | 用于配置新的 [XmlWriter](../) 实例的 [XmlWriterSettings](../../xmlwritersettings/) 对象。如果此值为 **nullptr**，则使用具有默认设置的 [XmlWriterSettings](../../xmlwritersettings/)。如果在使用 XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>) 方法时使用 [XmlWriter](../)，应使用 XslCompiledTransform::get_OutputSettings 获取具有正确设置的 [XmlWriterSettings](../../xmlwritersettings/) 对象。这可确保创建的 [XmlWriter](../) 对象具有正确的输出设置。 |

### 返回值

一个 [XmlWriter](../) 对象。

## XmlWriter::Create(const SharedPtr\<IO::Stream\>\&) 方法

使用指定的流创建一个新的 [XmlWriter](../) 实例。

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::Stream> &output)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | 您想写入的流。[XmlWriter](../) 以 XML 1.0 文本语法写入并追加到指定的流。 |

### 返回值

一个 [XmlWriter](../) 对象。

## XmlWriter::Create(const SharedPtr\<IO::Stream\>\&, SharedPtr\<XmlWriterSettings\>) 方法

使用流和 [XmlWriterSettings](../../xmlwritersettings/) 对象创建一个新的 [XmlWriter](../) 实例。

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::Stream> &output, SharedPtr<XmlWriterSettings> settings)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | 您想写入的流。[XmlWriter](../) 以 XML 1.0 文本语法写入并追加到指定的流。 |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | 用于配置新的 [XmlWriter](../) 实例的 [XmlWriterSettings](../../xmlwritersettings/) 对象。如果此值为 **nullptr**，则使用具有默认设置的 [XmlWriterSettings](../../xmlwritersettings/)。如果在使用 XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>) 方法时使用 [XmlWriter](../)，应使用 XslCompiledTransform::get_OutputSettings 获取具有正确设置的 [XmlWriterSettings](../../xmlwritersettings/) 对象。这可确保创建的 [XmlWriter](../) 对象具有正确的输出设置。 |

### 返回值

一个 [XmlWriter](../) 对象。

## XmlWriter::Create(const SharedPtr\<IO::TextWriter\>\&) 方法

使用指定的 TextWriter 创建一个新的 [XmlWriter](../) 实例。

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::TextWriter> &output)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | 您想写入的 TextWriter。[XmlWriter](../) 以 XML 1.0 文本语法写入并追加到指定的 TextWriter。 |

### 返回值

一个 [XmlWriter](../) 对象。

## XmlWriter::Create(const SharedPtr\<IO::TextWriter\>\&, SharedPtr\<XmlWriterSettings\>) 方法

使用 TextWriter 和 [XmlWriterSettings](../../xmlwritersettings/) 对象创建一个新的 [XmlWriter](../) 实例。

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::TextWriter> &output, SharedPtr<XmlWriterSettings> settings)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | 您想写入的 TextWriter。[XmlWriter](../) 以 XML 1.0 文本语法写入并追加到指定的 TextWriter。 |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | 用于配置新的 [XmlWriter](../) 实例的 [XmlWriterSettings](../../xmlwritersettings/) 对象。如果此值为 **nullptr**，则使用具有默认设置的 [XmlWriterSettings](../../xmlwritersettings/)。如果在使用 XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>) 方法时使用 [XmlWriter](../)，应使用 XslCompiledTransform::get_OutputSettings 获取具有正确设置的 [XmlWriterSettings](../../xmlwritersettings/) 对象。这可确保创建的 [XmlWriter](../) 对象具有正确的输出设置。 |

### 返回值

一个 [XmlWriter](../) 对象。

## XmlWriter::Create(const SharedPtr\<Text::StringBuilder\>\&) 方法

使用指定的 [Text::StringBuilder](../../../system.text/stringbuilder/) 创建一个新的 [XmlWriter](../) 实例。

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<Text::StringBuilder> &output)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\>\& | 要写入的 [Text::StringBuilder](../../../system.text/stringbuilder/)。[XmlWriter](../) 写入的内容会追加到 [Text::StringBuilder](../../../system.text/stringbuilder/)。 |

### 返回值

一个 [XmlWriter](../) 对象。

## XmlWriter::Create(const SharedPtr\<Text::StringBuilder\>\&, SharedPtr\<XmlWriterSettings\>) 方法

使用 [Text::StringBuilder](../../../system.text/stringbuilder/) 和 [XmlWriterSettings](../../xmlwritersettings/) 对象创建一个新的 [XmlWriter](../) 实例。

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<Text::StringBuilder> &output, SharedPtr<XmlWriterSettings> settings)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\>\& | 要写入的 [Text::StringBuilder](../../../system.text/stringbuilder/)。[XmlWriter](../) 写入的内容会追加到 [Text::StringBuilder](../../../system.text/stringbuilder/)。 |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | 用于配置新的 [XmlWriter](../) 实例的 [XmlWriterSettings](../../xmlwritersettings/) 对象。如果此值为 **nullptr**，则使用具有默认设置的 [XmlWriterSettings](../../xmlwritersettings/)。如果在使用 XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>) 方法时使用 [XmlWriter](../)，应使用 XslCompiledTransform::get_OutputSettings 获取具有正确设置的 [XmlWriterSettings](../../xmlwritersettings/) 对象。这可确保创建的 [XmlWriter](../) 对象具有正确的输出设置。 |

### 返回值

一个 [XmlWriter](../) 对象。

## XmlWriter::Create(const SharedPtr\<XmlWriter\>\&) 方法

使用指定的 [XmlWriter](../) 对象创建一个新的 [XmlWriter](../) 实例。

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<XmlWriter> &output)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../)\>\& | 您想用作底层写入器的 [XmlWriter](../) 对象。 |

### 返回值

一个包装在指定的 [XmlWriter](../) 对象之上的 [XmlWriter](../) 对象。

## XmlWriter::Create(const SharedPtr\<XmlWriter\>\&, SharedPtr\<XmlWriterSettings\>) 方法

使用指定的 [XmlWriter](../) 和 [XmlWriterSettings](../../xmlwritersettings/) 对象创建一个新的 [XmlWriter](../) 实例。

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<XmlWriter> &output, SharedPtr<XmlWriterSettings> settings)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../)\>\& | 您想用作底层写入器的 [XmlWriter](../) 对象。 |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | 用于配置新的 [XmlWriter](../) 实例的 [XmlWriterSettings](../../xmlwritersettings/) 对象。如果此值为 **nullptr**，则使用具有默认设置的 [XmlWriterSettings](../../xmlwritersettings/)。如果在使用 XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>) 方法时使用 [XmlWriter](../)，应使用 XslCompiledTransform::get_OutputSettings 获取具有正确设置的 [XmlWriterSettings](../../xmlwritersettings/) 对象。这可确保创建的 [XmlWriter](../) 对象具有正确的输出设置。 |

### 返回值

一个包装在指定的 [XmlWriter](../) 对象之上的 [XmlWriter](../) 对象。

## 另请参见

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlWriter](../)
* Class [String](../../../system/string/)
* Class [XmlWriterSettings](../../xmlwritersettings/)
* Class [Stream](../../../system.io/stream/)
* Class [TextWriter](../../../system.io/textwriter/)
* Class [StringBuilder](../../../system.text/stringbuilder/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)