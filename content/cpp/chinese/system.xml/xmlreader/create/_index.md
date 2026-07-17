---
title: Create()
second_title: Aspose.Slides for C++ API 参考
description: 使用指定的 URI 创建一个新的 XmlReader 实例。
type: docs
weight: 1015
url: /zh/system.xml/xmlreader/create/
---
## XmlReader::Create(const String\&) 方法

使用指定的 URI 创建一个新的 [XmlReader](../) 实例。

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const String &inputUri)
```

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | 包含 XML 数据的文件的 URI。[XmlUrlResolver](../../xmlurlresolver/) 类用于将路径转换为规范的数据表示。 |

### 返回值

用于读取流中 XML 数据的对象。

## XmlReader::Create(const String\&, const SharedPtr\<XmlReaderSettings\>\&) 方法

使用指定的 URI 和设置创建一个新的 [XmlReader](../) 实例。

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const String &inputUri, const SharedPtr<XmlReaderSettings> &settings)
```

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | 包含 XML 数据的文件的 URI。[XmlResolver](../../xmlresolver/) 对象在 [XmlReaderSettings](../../xmlreadersettings/) 对象上用于将路径转换为规范的数据表示。如果 XmlReaderSettings::get_XmlResolver 的值为 **nullptr**，则使用新的 [XmlUrlResolver](../../xmlurlresolver/) 对象。 |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\>\& | 新的 [XmlReader](../) 实例的设置。该值可以为 **nullptr**。 |

### 返回值

用于读取流中 XML 数据的对象。

## XmlReader::Create(const String\&, SharedPtr\<XmlReaderSettings\>, const SharedPtr\<XmlParserContext\>\&) 方法

使用指定的 URI、设置和用于解析的上下文信息创建一个新的 [XmlReader](../) 实例。

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const String &inputUri, SharedPtr<XmlReaderSettings> settings, const SharedPtr<XmlParserContext> &inputContext)
```

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | 包含 XML 数据的文件的 URI。[XmlResolver](../../xmlresolver/) 对象在 [XmlReaderSettings](../../xmlreadersettings/) 对象上用于将路径转换为规范的数据表示。如果 XmlReaderSettings::get_XmlResolver 的值为 **nullptr**，则使用新的 [XmlUrlResolver](../../xmlurlresolver/) 对象。 |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | 新的 [XmlReader](../) 实例的设置。该值可以为 **nullptr**。 |
| inputContext | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | 解析 XML 片段所需的上下文信息。上下文信息可以包括要使用的 [XmlNameTable](../../xmlnametable/)、编码、命名空间范围、当前的 **xml:lang** 和 **xml:space** 范围、基准 URI 以及文档类型定义。该值可以为 **nullptr**。 |

### 返回值

用于读取流中 XML 数据的对象。

## XmlReader::Create(const SharedPtr\<IO::Stream\>\&) 方法

使用指定的流并采用默认设置创建一个新的 [XmlReader](../) 实例。

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input)
```

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | 包含 XML 数据的流。[XmlReader](../) 扫描流的前几个字节，以查找字节顺序标记或其他编码标志。确定编码后，使用该编码继续读取流，并将输入解析为 (Unicode) 字符流。 |

### 返回值

用于读取流中 XML 数据的对象。

## XmlReader::Create(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlReaderSettings\>\&) 方法

使用指定的流和设置创建一个新的 [XmlReader](../) 实例。

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input, const SharedPtr<XmlReaderSettings> &settings)
```

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | 包含 XML 数据的流。[XmlReader](../) 扫描流的前几个字节，以查找字节顺序标记或其他编码标志。确定编码后，使用该编码继续读取流，并将输入解析为 (Unicode) 字符流。 |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\>\& | 新的 [XmlReader](../) 实例的设置。该值可以为 **nullptr**。 |

### 返回值

用于读取流中 XML 数据的对象。

## XmlReader::Create(const SharedPtr\<IO::Stream\>\&, SharedPtr\<XmlReaderSettings\>, const String\&) 方法

使用指定的流、基准 URI 和设置创建一个新的 [XmlReader](../) 实例。

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input, SharedPtr<XmlReaderSettings> settings, const String &baseUri)
```

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | 包含 XML 数据的流。[XmlReader](../) 扫描流的前几个字节，以查找字节顺序标记或其他编码标志。确定编码后，使用该编码继续读取流，并将输入解析为 (Unicode) 字符流。 |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | 新的 [XmlReader](../) 实例的设置。该值可以为 **nullptr**。 |
| baseUri | const [String](../../../system/string/)\& | 正在读取的实体或文档的基准 URI。该值可以为 **nullptr**。**[Security](../../../system.security/) 注** 基准 URI 用于解析 XML 文档的相对 URI。不要使用来自不可信来源的基准 URI。 |

### 返回值

用于读取流中 XML 数据的对象。

## XmlReader::Create(const SharedPtr\<IO::Stream\>\&, SharedPtr\<XmlReaderSettings\>, const SharedPtr\<XmlParserContext\>\&) 方法

使用指定的流、设置和用于解析的上下文信息创建一个新的 [XmlReader](../) 实例。

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input, SharedPtr<XmlReaderSettings> settings, const SharedPtr<XmlParserContext> &inputContext)
```

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | 包含 XML 数据的流。[XmlReader](../) 扫描流的前几个字节，以查找字节顺序标记或其他编码标志。确定编码后，使用该编码继续读取流，并将输入解析为 (Unicode) 字符流。 |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | 新的 [XmlReader](../) 实例的设置。该值可以为 **nullptr**。 |
| inputContext | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | 解析 XML 片段所需的上下文信息。上下文信息可以包括要使用的 [XmlNameTable](../../xmlnametable/)、编码、命名空间范围、当前的 **xml:lang** 和 **xml:space** 范围、基准 URI 以及文档类型定义。该值可以为 **nullptr**。 |

### 返回值

用于读取流中 XML 数据的对象。

## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&) 方法

使用指定的文本读取器创建一个新的 [XmlReader](../) 实例。

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input)
```

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | 用于读取 XML 数据的文本读取器。文本读取器返回 Unicode 字符流，因此 XML 声明中指定的编码不会被 XML 读取器用于解码数据流。 |

### 返回值

用于读取流中 XML 数据的对象。

## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&, const SharedPtr\<XmlReaderSettings\>\&) 方法

使用指定的文本读取器和设置创建一个新的 [XmlReader](../) 实例。

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input, const SharedPtr<XmlReaderSettings> &settings)
```

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | 用于读取 XML 数据的文本读取器。文本读取器返回 Unicode 字符流，因此 XML 声明中指定的编码不会被 XML 读取器用于解码数据流。 |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\>\& | 新的 [XmlReader](../) 的设置。该值可以为 **nullptr**。 |

### 返回值

用于读取流中 XML 数据的对象。

## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&, SharedPtr\<XmlReaderSettings\>, const String\&) 方法

使用指定的文本读取器、设置和基准 URI 创建一个新的 [XmlReader](../) 实例。

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input, SharedPtr<XmlReaderSettings> settings, const String &baseUri)
```

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | 用于读取 XML 数据的文本读取器。文本读取器返回 Unicode 字符流，因此 XML 声明中指定的编码不会被 [XmlReader](../) 用于解码数据流。 |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | 新的 [XmlReader](../) 实例的设置。该值可以为 **nullptr**。 |
| baseUri | const [String](../../../system/string/)\& | 正在读取的实体或文档的基准 URI。该值可以为 **nullptr**。**[Security](../../../system.security/) 注** 基准 URI 用于解析 XML 文档的相对 URI。不要使用来自不可信来源的基准 URI。 |

### 返回值

用于读取流中 XML 数据的对象。

## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&, SharedPtr\<XmlReaderSettings\>, const SharedPtr\<XmlParserContext\>\&) 方法

使用指定的文本读取器、设置和用于解析的上下文信息创建一个新的 [XmlReader](../) 实例。

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input, SharedPtr<XmlReaderSettings> settings, const SharedPtr<XmlParserContext> &inputContext)
```

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | 用于读取 XML 数据的文本读取器。文本读取器返回 Unicode 字符流，因此 XML 声明中指定的编码不会被 XML 读取器用于解码数据流。 |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | 新的 [XmlReader](../) 实例的设置。该值可以为 **nullptr**。 |
| inputContext | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | 解析 XML 片段所需的上下文信息。上下文信息可以包括要使用的 [XmlNameTable](../../xmlnametable/)、编码、命名空间范围、当前的 **xml:lang** 和 **xml:space** 范围、基准 URI 以及文档类型定义。该值可以为 **nullptr**。 |

### 返回值

用于读取流中 XML 数据的对象。

## XmlReader::Create(const SharedPtr\<XmlReader\>\&, SharedPtr\<XmlReaderSettings\>) 方法

使用指定的 XML 读取器和设置创建一个新的 [XmlReader](../) 实例。

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<XmlReader> &reader, SharedPtr<XmlReaderSettings> settings)
```

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../)\>\& | 您希望用作底层 XML 读取器的对象。 |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | 新的 [XmlReader](../) 实例的设置。[XmlReaderSettings](../../xmlreadersettings/) 对象的兼容级别必须与底层读取器的兼容级别匹配，或设置为 [ConformanceLevel::Auto](../../conformancelevel/)。 |

### 返回值

包装在指定的 [XmlReader](../) 对象周围的对象。

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [XmlReader](../)
* 类 [String](../../../system/string/)
* 类 [XmlReaderSettings](../../xmlreadersettings/)
* 类 [XmlParserContext](../../xmlparsercontext/)
* 类 [Stream](../../../system.io/stream/)
* 类 [TextReader](../../../system.io/textreader/)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)