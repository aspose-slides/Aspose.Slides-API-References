---
title: XmlTextReader()
second_title: Aspose.Slides for C++ API 参考
description: 使用指定的流初始化 XmlTextReader 类的新实例。
type: docs
weight: 482
url: /zh/system.xml/xmltextreader/xmltextreader/
---
## XmlTextReader::XmlTextReader(const SharedPtr\<IO::Stream\>\&) constructor


使用指定的流初始化 [XmlTextReader](../) 类的新实例。

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::Stream> &input)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | 包含要读取的 XML 数据的流。 |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::Stream\>\&) constructor


使用指定的 URL 和流初始化 [XmlTextReader](../) 类的新实例。

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::Stream> &input)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | 用于解析外部资源的 URL。[XmlTextReader::get_BaseURI](../get_baseuri/) 被设置为该值。 |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | 包含要读取的 XML 数据的流。 |

## XmlTextReader::XmlTextReader(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlNameTable\>\&) constructor


使用指定的流和 [XmlNameTable](../../xmlnametable/) 初始化 [XmlTextReader](../) 类的新实例。

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::Stream> &input, const SharedPtr<XmlNameTable> &nt)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | 包含要读取的 XML 数据的流。 |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | 要使用的 [XmlNameTable](../../xmlnametable/)。 |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlNameTable\>\&) constructor


使用指定的 URL、流和 [XmlNameTable](../../xmlnametable/) 初始化 [XmlTextReader](../) 类的新实例。

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::Stream> &input, const SharedPtr<XmlNameTable> &nt)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | 用于解析外部资源的 URL。[XmlTextReader::get_BaseURI](../get_baseuri/) 被设置为该值。如果 **url** 为 **nullptr**，则 **BaseURI** 被设置为 [String::Empty](../../../system/string/empty/)。 |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | 包含要读取的 XML 数据的流。 |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | 要使用的 [XmlNameTable](../../xmlnametable/)。 |

## XmlTextReader::XmlTextReader(const SharedPtr\<IO::TextReader\>\&) constructor


使用指定的 TextReader 初始化 [XmlTextReader](../) 类的新实例。

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::TextReader> &input)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | 包含要读取的 XML 数据的 TextReader。 |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::TextReader\>\&) constructor


使用指定的 URL 和 TextReader 初始化 [XmlTextReader](../) 类的新实例。

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::TextReader> &input)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | 用于解析外部资源的 URL。[XmlTextReader::get_BaseURI](../get_baseuri/) 被设置为该值。 |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | 包含要读取的 XML 数据的 TextReader。 |

## XmlTextReader::XmlTextReader(const SharedPtr\<IO::TextReader\>\&, const SharedPtr\<XmlNameTable\>\&) constructor


使用指定的 TextReader 和 [XmlNameTable](../../xmlnametable/) 初始化 [XmlTextReader](../) 类的新实例。

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::TextReader> &input, const SharedPtr<XmlNameTable> &nt)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | 包含要读取的 XML 数据的 TextReader。 |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | 要使用的 [XmlNameTable](../../xmlnametable/)。 |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::TextReader\>\&, const SharedPtr\<XmlNameTable\>\&) constructor


使用指定的 URL、TextReader 和 [XmlNameTable](../../xmlnametable/) 初始化 [XmlTextReader](../) 类的新实例。

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::TextReader> &input, const SharedPtr<XmlNameTable> &nt)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | 用于解析外部资源的 URL。[XmlTextReader::get_BaseURI](../get_baseuri/) 被设置为该值。如果 **url** 为 **nullptr**，则 **BaseURI** 被设置为 [String::Empty](../../../system/string/empty/)。 |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | 包含要读取的 XML 数据的 TextReader。 |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | 要使用的 [XmlNameTable](../../xmlnametable/)。 |

## XmlTextReader::XmlTextReader(const SharedPtr\<IO::Stream\>\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) constructor


使用指定的流、XmlNodeType 和 [XmlParserContext](../../xmlparsercontext/) 初始化 [XmlTextReader](../) 类的新实例。

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::Stream> &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| xmlFragment | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | 包含要解析的 XML 片段的流。 |
| fragType | [XmlNodeType](../../xmlnodetype/) | XML 片段的 XmlNodeType。这还决定片段可以包含的内容。 |
| context | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | 用于解析 **xmlFragment** 的 [XmlParserContext](../../xmlparsercontext/)。它包括要使用的 [XmlNameTable](../../xmlnametable/)、编码、命名空间范围、当前的 **xml:lang** 和 **xml:space** 范围。 |

## XmlTextReader::XmlTextReader(const String\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) constructor


使用指定的字符串、XmlNodeType 和 [XmlParserContext](../../xmlparsercontext/) 初始化 [XmlTextReader](../) 类的新实例。

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| xmlFragment | const [String](../../../system/string/)\& | 包含要解析的 XML 片段的字符串。 |
| fragType | [XmlNodeType](../../xmlnodetype/) | XML 片段的 XmlNodeType。这还决定片段字符串可以包含的内容。 |
| context | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | 用于解析 **xmlFragment** 的 [XmlParserContext](../../xmlparsercontext/)。它包括要使用的 [XmlNameTable](../../xmlnametable/)、编码、命名空间范围、当前的 **xml:lang** 和 **xml:space** 范围。 |

## XmlTextReader::XmlTextReader(const String\&) constructor


使用指定的文件初始化 [XmlTextReader](../) 类的新实例。

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | 包含 XML 数据的文件的 URL。[XmlTextReader::get_BaseURI](../get_baseuri/) 被设置为该值。 |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<XmlNameTable\>\&) constructor


使用指定的文件和 [XmlNameTable](../../xmlnametable/) 初始化 [XmlTextReader](../) 类的新实例。

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<XmlNameTable> &nt)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | 包含 XML 数据的文件的 URL。 |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | 要使用的 [XmlNameTable](../../xmlnametable/)。 |

## 另请参见

* 枚举 [XmlNodeType](../../xmlnodetype/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [Stream](../../../system.io/stream/)
* 类 [XmlTextReader](../)
* 类 [String](../../../system/string/)
* 类 [XmlNameTable](../../xmlnametable/)
* 类 [TextReader](../../../system.io/textreader/)
* 类 [XmlParserContext](../../xmlparsercontext/)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)