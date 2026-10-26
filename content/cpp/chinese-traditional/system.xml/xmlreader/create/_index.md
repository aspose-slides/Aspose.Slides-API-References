---
title: Create()
second_title: Aspose.Slides for C++ API 參考
description: 使用指定的 URI 建立新的 XmlReader 實例。
type: docs
weight: 1015
url: /zh-hant/system.xml/xmlreader/create/
---
## XmlReader::Create(const String\&) 方法

使用指定的 URI 建立新的 [XmlReader](../) 實例。

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const String &inputUri)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | 包含 XML 資料之檔案的 URI。[XmlUrlResolver](../../xmlurlresolver/) 類別用於將路徑轉換為正規化的資料表示。 |

### 返回值

用於在串流中讀取 XML 資料的物件。

## XmlReader::Create(const String\&, const SharedPtr\<XmlReaderSettings\>\&) 方法

使用指定的 URI 和設定建立新的 [XmlReader](../) 實例。

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const String &inputUri, const SharedPtr<XmlReaderSettings> &settings)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | 包含 XML 資料之檔案的 URI。[XmlResolver](../../xmlresolver/) 物件位於 [XmlReaderSettings](../../xmlreadersettings/) 物件上，用於將路徑轉換為正規化的資料表示。若 XmlReaderSettings::get_XmlResolver 的值為 **nullptr**，則會使用新的 [XmlUrlResolver](../../xmlurlresolver/) 物件。 |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\>\& | 新的 [XmlReader](../) 實例的設定。此值可以為 **nullptr**。 |

### 返回值

用於在串流中讀取 XML 資料的物件。

## XmlReader::Create(const String\&, SharedPtr\<XmlReaderSettings\>, const SharedPtr\<XmlParserContext\>\&) 方法

使用指定的 URI、設定與解析上下文資訊建立新的 [XmlReader](../) 實例。

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const String &inputUri, SharedPtr<XmlReaderSettings> settings, const SharedPtr<XmlParserContext> &inputContext)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | 包含 XML 資料之檔案的 URI。[XmlResolver](../../xmlresolver/) 物件位於 [XmlReaderSettings](../../xmlreadersettings/) 物件上，用於將路徑轉換為正規化的資料表示。若 XmlReaderSettings::get_XmlResolver 的值為 **nullptr**，則會使用新的 [XmlUrlResolver](../../xmlurlresolver/) 物件。 |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | 新的 [XmlReader](../) 實例的設定。此值可以為 **nullptr**。 |
| inputContext | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | 解析 XML 片段所需的上下文資訊。此資訊可以包含要使用的 [XmlNameTable](../../xmlnametable/)、編碼、命名空間範圍、目前的 **xml:lang** 與 **xml:space** 範圍、基礎 URI 與文件類型定義。此值可以為 **nullptr**。 |

### 返回值

用於在串流中讀取 XML 資料的物件。

## XmlReader::Create(const SharedPtr\<IO::Stream\>\&) 方法

使用指定的串流（預設設定）建立新的 [XmlReader](../) 實例。

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | 包含 XML 資料的串流。[XmlReader](../) 會掃描串流的前幾個位元組，以尋找位元順序標記或其他編碼訊號。確定編碼後，該編碼將用於繼續讀取串流，並將輸入視為 (Unicode) 字元串流進行解析。 |

### 返回值

用於在串流中讀取 XML 資料的物件。

## XmlReader::Create(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlReaderSettings\>\&) 方法

使用指定的串流和設定建立新的 [XmlReader](../) 實例。

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input, const SharedPtr<XmlReaderSettings> &settings)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | 包含 XML 資料的串流。[XmlReader](../) 會掃描串流的前幾個位元組，以尋找位元順序標記或其他編碼訊號。確定編碼後，該編碼將用於繼續讀取串流，並將輸入視為 (Unicode) 字元串流進行解析。 |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\>\& | 新的 [XmlReader](../) 實例的設定。此值可以為 **nullptr**。 |

### 返回值

用於在串流中讀取 XML 資料的物件。

## XmlReader::Create(const SharedPtr\<IO::Stream\>\&, SharedPtr\<XmlReaderSettings\>, const String\&) 方法

使用指定的串流、基礎 URI 與設定建立新的 [XmlReader](../) 實例。

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input, SharedPtr<XmlReaderSettings> settings, const String &baseUri)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | 包含 XML 資料的串流。[XmlReader](../) 會掃描串流的前幾個位元組，以尋找位元順序標記或其他編碼訊號。確定編碼後，該編碼將用於繼續讀取串流，並將輸入視為 (Unicode) 字元串流進行解析。 |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | 新的 [XmlReader](../) 實例的設定。此值可以為 **nullptr**。 |
| baseUri | const [String](../../../system/string/)\& | 讀取的實體或文件的基礎 URI。此值可以為 **nullptr**。 **[Security](../../../system.security/) Note** 基礎 URI 用於解析 XML 文件的相對 URI。請勿使用來自不可信來源的基礎 URI。 |

### 返回值

用於在串流中讀取 XML 資料的物件。

## XmlReader::Create(const SharedPtr\<IO::Stream\>\&, SharedPtr\<XmlReaderSettings\>, const SharedPtr\<XmlParserContext\>\&) 方法

使用指定的串流、設定與解析上下文資訊建立新的 [XmlReader](../) 實例。

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input, SharedPtr<XmlReaderSettings> settings, const SharedPtr<XmlParserContext> &inputContext)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | 包含 XML 資料的串流。[XmlReader](../) 會掃描串流的前幾個位元組，以尋找位元順序標記或其他編碼訊號。確定編碼後，該編碼將用於繼續讀取串流，並將輸入視為 (Unicode) 字元串流進行解析。 |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | 新的 [XmlReader](../) 實例的設定。此值可以為 **nullptr**。 |
| inputContext | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | 解析 XML 片段所需的上下文資訊。此資訊可以包含要使用的 [XmlNameTable](../../xmlnametable/)、編碼、命名空間範圍、目前的 **xml:lang** 與 **xml:space** 範圍、基礎 URI 與文件類型定義。此值可以為 **nullptr**。 |

### 返回值

用於在串流中讀取 XML 資料的物件。

## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&) 方法

使用指定的文字讀取器建立新的 [XmlReader](../) 實例。

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | 用於讀取 XML 資料的文字讀取器。文字讀取器會返回 Unicode 字元串流，因而 XML 宣告中指定的編碼不會被 XML 讀取器用來解碼資料串流。 |

### 返回值

用於在串流中讀取 XML 資料的物件。

## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&, const SharedPtr\<XmlReaderSettings\>\&) 方法

使用指定的文字讀取器與設定建立新的 [XmlReader](../) 實例。

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input, const SharedPtr<XmlReaderSettings> &settings)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | 用於讀取 XML 資料的文字讀取器。文字讀取器會返回 Unicode 字元串流，因而 XML 宣告中指定的編碼不會被 XML 讀取器用來解碼資料串流。 |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\>\& | 新的 [XmlReader](../) 的設定。此值可以為 **nullptr**。 |

### 返回值

用於在串流中讀取 XML 資料的物件。

## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&, SharedPtr\<XmlReaderSettings\>, const String\&) 方法

使用指定的文字讀取器、設定與基礎 URI 建立新的 [XmlReader](../) 實例。

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input, SharedPtr<XmlReaderSettings> settings, const String &baseUri)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | 用於讀取 XML 資料的文字讀取器。文字讀取器會返回 Unicode 字元串流，因而 XML 宣告中指定的編碼不會被 [XmlReader](../) 用來解碼資料串流。 |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | 新的 [XmlReader](../) 實例的設定。此值可以為 **nullptr**。 |
| baseUri | const [String](../../../system/string/)\& | 讀取的實體或文件的基礎 URI。此值可以為 **nullptr**。 **[Security](../../../system.security/) Note** 基礎 URI 用於解析 XML 文件的相對 URI。請勿使用來自不可信來源的基礎 URI。 |

### 返回值

用於在串流中讀取 XML 資料的物件。

## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&, SharedPtr\<XmlReaderSettings\>, const SharedPtr\<XmlParserContext\>\&) 方法

使用指定的文字讀取器、設定與解析上下文資訊建立新的 [XmlReader](../) 實例。

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input, SharedPtr<XmlReaderSettings> settings, const SharedPtr<XmlParserContext> &inputContext)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | 用於讀取 XML 資料的文字讀取器。文字讀取器會返回 Unicode 字元串流，因而 XML 宣告中指定的編碼不會被 XML 讀取器用來解碼資料串流。 |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | 新的 [XmlReader](../) 實例的設定。此值可以為 **nullptr**。 |
| inputContext | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | 解析 XML 片段所需的上下文資訊。此資訊可以包含要使用的 [XmlNameTable](../../xmlnametable/)、編碼、命名空間範圍、目前的 **xml:lang** 與 **xml:space** 範圍、基礎 URI 與文件類型定義。此值可以為 **nullptr**。 |

### 返回值

用於在串流中讀取 XML 資料的物件。

## XmlReader::Create(const SharedPtr\<XmlReader\>\&, SharedPtr\<XmlReaderSettings\>) 方法

使用指定的 XML 讀取器與設定建立新的 [XmlReader](../) 實例。

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<XmlReader> &reader, SharedPtr<XmlReaderSettings> settings)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../)\>\& | 您想要作為底層 XML 讀取器使用的物件。 |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | 新的 [XmlReader](../) 實例的設定。[XmlReaderSettings](../../xmlreadersettings/) 物件的相容等級必須與底層讀取器的相容等級相同，或必須設定為 [ConformanceLevel::Auto](../../conformancelevel/)。 |

### 返回值

包裝在指定的 [XmlReader](../) 物件周圍的物件。

## 另見

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../)
* Class [String](../../../system/string/)
* Class [XmlReaderSettings](../../xmlreadersettings/)
* Class [XmlParserContext](../../xmlparsercontext/)
* Class [Stream](../../../system.io/stream/)
* Class [TextReader](../../../system.io/textreader/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)