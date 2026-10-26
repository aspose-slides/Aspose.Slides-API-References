---
title: Create()
second_title: Aspose.Slides for C++ API 參考
description: 使用指定的檔名建立新的 XmlWriter 實例。
type: docs
weight: 469
url: /zh-hant/system.xml/xmlwriter/create/
---
## XmlWriter::Create(const String\&) 方法

使用指定的檔名建立新的 [XmlWriter](../) 實例。

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const String &outputFileName)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| outputFileName | const [String](../../../system/string/)\& | 您想寫入的檔案。[XmlWriter](../) 會在指定路徑建立檔案，並以 XML 1.0 文字語法寫入。**outputFileName** 必須是檔案系統路徑。 |

### 回傳值

一個 [XmlWriter](../) 物件。

## XmlWriter::Create(const String\&, SharedPtr\<XmlWriterSettings\>) 方法

使用檔名和 [XmlWriterSettings](../../xmlwritersettings/) 物件建立新的 [XmlWriter](../) 實例。

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const String &outputFileName, SharedPtr<XmlWriterSettings> settings)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| outputFileName | const [String](../../../system/string/)\& | 您想寫入的檔案。[XmlWriter](../) 會在指定路徑建立檔案，並以 XML 1.0 文字語法寫入。**outputFileName** 必須是檔案系統路徑。 |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | 用於設定新 [XmlWriter](../) 實例的 [XmlWriterSettings](../../xmlwritersettings/) 物件。如果此為 **nullptr**，則使用具有預設設定的 [XmlWriterSettings](../../xmlwritersettings/)。如果 [XmlWriter](../) 正與 XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>) 方法一起使用，應使用 XslCompiledTransform::get_OutputSettings 取得正確設定的 [XmlWriterSettings](../../xmlwritersettings/) 物件。這確保建立的 [XmlWriter](../) 物件具有正確的輸出設定。 |

### 回傳值

一個 [XmlWriter](../) 物件。

## XmlWriter::Create(const SharedPtr\<IO::Stream\>\&) 方法

使用指定的串流建立新的 [XmlWriter](../) 實例。

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::Stream> &output)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | 您想寫入的串流。[XmlWriter](../) 會以 XML 1.0 文字語法寫入並附加至指定的串流。 |

### 回傳值

一個 [XmlWriter](../) 物件。

## XmlWriter::Create(const SharedPtr\<IO::Stream\>\&, SharedPtr\<XmlWriterSettings\>) 方法

使用串流和 [XmlWriterSettings](../../xmlwritersettings/) 物件建立新的 [XmlWriter](../) 實例。

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::Stream> &output, SharedPtr<XmlWriterSettings> settings)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | 您想寫入的串流。[XmlWriter](../) 會以 XML 1.0 文字語法寫入並附加至指定的串流。 |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | 用於設定新 [XmlWriter](../) 實例的 [XmlWriterSettings](../../xmlwritersettings/) 物件。如果此為 **nullptr**，則使用具有預設設定的 [XmlWriterSettings](../../xmlwritersettings/)。如果 [XmlWriter](../) 正與 XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>) 方法一起使用，應使用 XslCompiledTransform::get_OutputSettings 取得正確設定的 [XmlWriterSettings](../../xmlwritersettings/) 物件。這確保建立的 [XmlWriter](../) 物件具有正確的輸出設定。 |

### 回傳值

一個 [XmlWriter](../) 物件。

## XmlWriter::Create(const SharedPtr\<IO::TextWriter\>\&) 方法

使用指定的 TextWriter 建立新的 [XmlWriter](../) 實例。

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::TextWriter> &output)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | 您想寫入的 TextWriter。[XmlWriter](../) 會以 XML 1.0 文字語法寫入並附加至指定的 TextWriter。 |

### 回傳值

一個 [XmlWriter](../) 物件。

## XmlWriter::Create(const SharedPtr\<IO::TextWriter\>\&, SharedPtr\<XmlWriterSettings\>) 方法

使用 TextWriter 與 [XmlWriterSettings](../../xmlwritersettings/) 物件建立新的 [XmlWriter](../) 實例。

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::TextWriter> &output, SharedPtr<XmlWriterSettings> settings)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | 您想寫入的 TextWriter。[XmlWriter](../) 會以 XML 1.0 文字語法寫入並附加至指定的 TextWriter。 |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | 用於設定新 [XmlWriter](../) 實例的 [XmlWriterSettings](../../xmlwritersettings/) 物件。如果此為 **nullptr**，則使用具有預設設定的 [XmlWriterSettings](../../xmlwritersettings/)。如果 [XmlWriter](../) 正與 XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>) 方法一起使用，應使用 XslCompiledTransform::get_OutputSettings 取得正確設定的 [XmlWriterSettings](../../xmlwritersettings/) 物件。這確保建立的 [XmlWriter](../) 物件具有正確的輸出設定。 |

### 回傳值

一個 [XmlWriter](../) 物件。

## XmlWriter::Create(const SharedPtr\<Text::StringBuilder\>\&) 方法

使用指定的 [Text::StringBuilder](../../../system.text/stringbuilder/) 建立新的 [XmlWriter](../) 實例。

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<Text::StringBuilder> &output)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\>\& | [Text::StringBuilder](../../../system.text/stringbuilder/) 用於寫入。[XmlWriter](../) 所寫入的內容會附加至 [Text::StringBuilder](../../../system.text/stringbuilder/)。 |

### 回傳值

一個 [XmlWriter](../) 物件。

## XmlWriter::Create(const SharedPtr\<Text::StringBuilder\>\&, SharedPtr\<XmlWriterSettings\>) 方法

使用 [Text::StringBuilder](../../../system.text/stringbuilder/) 與 [XmlWriterSettings](../../xmlwritersettings/) 物件建立新的 [XmlWriter](../) 實例。

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<Text::StringBuilder> &output, SharedPtr<XmlWriterSettings> settings)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\>\& | [Text::StringBuilder](../../../system.text/stringbuilder/) 用於寫入。[XmlWriter](../) 所寫入的內容會附加至 [Text::StringBuilder](../../../system.text/stringbuilder/)。 |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | 用於設定新 [XmlWriter](../) 實例的 [XmlWriterSettings](../../xmlwritersettings/) 物件。如果此為 **nullptr**，則使用具有預設設定的 [XmlWriterSettings](../../xmlwritersettings/)。如果 [XmlWriter](../) 正與 XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>) 方法一起使用，應使用 XslCompiledTransform::get_OutputSettings 取得正確設定的 [XmlWriterSettings](../../xmlwritersettings/) 物件。這確保建立的 [XmlWriter](../) 物件具有正確的輸出設定。 |

### 回傳值

一個 [XmlWriter](../) 物件。

## XmlWriter::Create(const SharedPtr\<XmlWriter\>\&) 方法

使用指定的 [XmlWriter](../) 物件建立新的 [XmlWriter](../) 實例。

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<XmlWriter> &output)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../)\>\& | 您想作為底層寫入器使用的 [XmlWriter](../) 物件。 |

### 回傳值

一個包裝於指定 [XmlWriter](../) 物件之上的 [XmlWriter](../) 物件。

## XmlWriter::Create(const SharedPtr\<XmlWriter\>\&, SharedPtr\<XmlWriterSettings\>) 方法

使用指定的 [XmlWriter](../) 與 [XmlWriterSettings](../../xmlwritersettings/) 物件建立新的 [XmlWriter](../) 實例。

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<XmlWriter> &output, SharedPtr<XmlWriterSettings> settings)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../)\>\& | 您想作為底層寫入器使用的 [XmlWriter](../) 物件。 |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | 用於設定新 [XmlWriter](../) 實例的 [XmlWriterSettings](../../xmlwritersettings/) 物件。如果此為 **nullptr**，則使用具有預設設定的 [XmlWriterSettings](../../xmlwritersettings/)。如果 [XmlWriter](../) 正與 XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>) 方法一起使用，應使用 XslCompiledTransform::get_OutputSettings 取得正確設定的 [XmlWriterSettings](../../xmlwritersettings/) 物件。這確保建立的 [XmlWriter](../) 物件具有正確的輸出設定。 |

### 回傳值

一個包裝於指定 [XmlWriter](../) 物件之上的 [XmlWriter](../) 物件。

## 參見

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlWriter](../)
* Class [String](../../../system/string/)
* Class [XmlWriterSettings](../../xmlwritersettings/)
* Class [Stream](../../../system.io/stream/)
* Class [TextWriter](../../../system.io/textwriter/)
* Class [StringBuilder](../../../system.text/stringbuilder/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)