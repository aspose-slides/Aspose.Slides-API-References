---
title: XmlTextReader()
second_title: Aspose.Slides for C++ API 參考
description: 使用指定的串流初始化 XmlTextReader 類別的新執行個體。
type: docs
weight: 482
url: /zh-hant/system.xml/xmltextreader/xmltextreader/
---
## XmlTextReader::XmlTextReader(const SharedPtr\<IO::Stream\>\&) 建構函式

使用指定的串流初始化 [XmlTextReader](../) 類別的新執行個體。

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::Stream> &input)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | 包含要讀取之 XML 資料的串流。 |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::Stream\>\&) 建構函式

使用指定的 URL 與串流初始化 [XmlTextReader](../) 類別的新執行個體。

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::Stream> &input)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | 用於解析外部資源的 URL。[XmlTextReader::get_BaseURI](../get_baseuri/) 會設定為此值。 |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | 包含要讀取之 XML 資料的串流。 |

## XmlTextReader::XmlTextReader(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlNameTable\>\&) 建構函式

使用指定的串流與 [XmlNameTable](../../xmlnametable/) 初始化 [XmlTextReader](../) 類別的新執行個體。

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::Stream> &input, const SharedPtr<XmlNameTable> &nt)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | 包含要讀取之 XML 資料的串流。 |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | 要使用的 [XmlNameTable](../../xmlnametable/)。 |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlNameTable\>\&) 建構函式

使用指定的 URL、串流與 [XmlNameTable](../../xmlnametable/) 初始化 [XmlTextReader](../) 類別的新執行個體。

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::Stream> &input, const SharedPtr<XmlNameTable> &nt)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | 用於解析外部資源的 URL。[XmlTextReader::get_BaseURI](../get_baseuri/) 會設定為此值。若 **url** 為 **nullptr**，則 **BaseURI** 會設定為 [String::Empty](../../../system/string/empty/)。 |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | 包含要讀取之 XML 資料的串流。 |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | 要使用的 [XmlNameTable](../../xmlnametable/)。 |

## XmlTextReader::XmlTextReader(const SharedPtr\<IO::TextReader\>\&) 建構函式

使用指定的 TextReader 初始化 [XmlTextReader](../) 類別的新執行個體。

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::TextReader> &input)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | 包含要讀取之 XML 資料的 TextReader。 |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::TextReader\>\&) 建構函式

使用指定的 URL 與 TextReader 初始化 [XmlTextReader](../) 類別的新執行個體。

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::TextReader> &input)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | 用於解析外部資源的 URL。[XmlTextReader::get_BaseURI](../get_baseuri/) 會設定為此值。 |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | 包含要讀取之 XML 資料的 TextReader。 |

## XmlTextReader::XmlTextReader(const SharedPtr\<IO::TextReader\>\&, const SharedPtr\<XmlNameTable\>\&) 建構函式

使用指定的 TextReader 與 [XmlNameTable](../../xmlnametable/) 初始化 [XmlTextReader](../) 類別的新執行個體。

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::TextReader> &input, const SharedPtr<XmlNameTable> &nt)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | 包含要讀取之 XML 資料的 TextReader。 |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | 要使用的 [XmlNameTable](../../xmlnametable/)。 |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::TextReader\>\&, const SharedPtr\<XmlNameTable\>\&) 建構函式

使用指定的 URL、TextReader 與 [XmlNameTable](../../xmlnametable/) 初始化 [XmlTextReader](../) 類別的新執行個體。

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::TextReader> &input, const SharedPtr<XmlNameTable> &nt)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | 用於解析外部資源的 URL。[XmlTextReader::get_BaseURI](../get_baseuri/) 會設定為此值。若 **url** 為 **nullptr**，則 **BaseURI** 會設定為 [String::Empty](../../../system/string/empty/)。 |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | 包含要讀取之 XML 資料的 TextReader。 |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | 要使用的 [XmlNameTable](../../xmlnametable/)。 |

## XmlTextReader::XmlTextReader(const SharedPtr\<IO::Stream\>\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) 建構函式

使用指定的串流、XmlNodeType 與 [XmlParserContext](../../xmlparsercontext/) 初始化 [XmlTextReader](../) 類別的新執行個體。

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::Stream> &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| xmlFragment | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | 包含要解析之 XML 片段的串流。 |
| fragType | [XmlNodeType](../../xmlnodetype/) | XML 片段的 XmlNodeType。此同時決定片段可包含的內容。 |
| context | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | 解析 **xmlFragment** 時所使用的 [XmlParserContext](../../xmlparsercontext/)。其中包括要使用的 [XmlNameTable](../../xmlnametable/)、編碼、命名空間範圍、目前的 **xml:lang** 與 **xml:space** 範圍。 |

## XmlTextReader::XmlTextReader(const String\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) 建構函式

使用指定的字串、XmlNodeType 與 [XmlParserContext](../../xmlparsercontext/) 初始化 [XmlTextReader](../) 類別的新執行個體。

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| xmlFragment | const [String](../../../system/string/)\& | 包含要解析之 XML 片段的字串。 |
| fragType | [XmlNodeType](../../xmlnodetype/) | XML 片段的 XmlNodeType。此同時決定片段字串可包含的內容。 |
| context | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | 解析 **xmlFragment** 時所使用的 [XmlParserContext](../../xmlparsercontext/)。其中包括要使用的 [XmlNameTable](../../xmlnametable/)、編碼、命名空間範圍、目前的 **xml:lang** 與 **xml:space** 範圍。 |

## XmlTextReader::XmlTextReader(const String\&) 建構函式

使用指定的檔案初始化 [XmlTextReader](../) 類別的新執行個體。

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | 包含 XML 資料之檔案的 URL。[XmlTextReader::get_BaseURI](../get_baseuri/) 會設定為此值。 |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<XmlNameTable\>\&) 建構函式

使用指定的檔案與 [XmlNameTable](../../xmlnametable/) 初始化 [XmlTextReader](../) 類別的新執行個體。

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<XmlNameTable> &nt)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | 包含要讀取之 XML 資料之檔案的 URL。 |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | 要使用的 [XmlNameTable](../../xmlnametable/)。 |

## 另請參閱

* Enum [XmlNodeType](../../xmlnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [XmlTextReader](../)
* Class [String](../../../system/string/)
* Class [XmlNameTable](../../xmlnametable/)
* Class [TextReader](../../../system.io/textreader/)
* Class [XmlParserContext](../../xmlparsercontext/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)