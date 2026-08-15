---
title: Transform()
second_title: Aspose.Slides for C++ API 參考
description: 使用 IXPathNavigable 物件指定的輸入文件執行轉換，並將結果輸出至 XmlWriter。
type: docs
weight: 40
url: /zh-hant/system.xml.xsl/xslcompiledtransform/transform/
---
## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XmlWriter\>\&) 方法

使用 IXPathNavigable 物件指定的輸入文件執行轉換，並將結果輸出至 [XmlWriter](../../../system.xml/xmlwriter/)。

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XmlWriter> &results)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | 實作 IXPathNavigable 介面的物件。它可以是 [XmlNode](../../../system.xml/xmlnode/)（通常為 [XmlDocument](../../../system.xml/xmldocument/)），或者是包含要轉換資料的 XPathDocument。 |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | 您想要輸出的 [XmlWriter](../../../system.xml/xmlwriter/)。如果樣式表包含 **xsl:output** 元素，您應該使用從 [XslCompiledTransform::get_OutputSettings](../get_outputsettings/) 值返回的 [XmlWriterSettings](../../../system.xml/xmlwritersettings/) 物件建立 [XmlWriter](../../../system.xml/xmlwriter/)。這可確保 [XmlWriter](../../../system.xml/xmlwriter/) 具有正確的輸出設定。 |

## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) 方法

使用 IXPathNavigable 物件指定的輸入文件執行轉換，並將結果輸出至 [XmlWriter](../../../system.xml/xmlwriter/)。[XsltArgumentList](../../xsltargumentlist/) 提供額外的執行時參數。

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | 實作 IXPathNavigable 介面的物件。它可以是 [XmlNode](../../../system.xml/xmlnode/)（通常為 [XmlDocument](../../../system.xml/xmldocument/)），或者是包含要轉換資料的 XPathDocument。 |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | 包含用於轉換之輸入的具有命名空間限定的參數的 [XsltArgumentList](../../xsltargumentlist/)。此值可以為 **nullptr**。 |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | 您想要輸出的 [XmlWriter](../../../system.xml/xmlwriter/)。如果樣式表包含 **xsl:output** 元素，您應該使用從 [XslCompiledTransform::get_OutputSettings](../get_outputsettings/) 值返回的 [XmlWriterSettings](../../../system.xml/xmlwritersettings/) 物件建立 [XmlWriter](../../../system.xml/xmlwriter/)。這可確保 [XmlWriter](../../../system.xml/xmlwriter/) 具有正確的輸出設定。 |

## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) 方法

使用 IXPathNavigable 物件指定的輸入文件執行轉換，並將結果輸出至 TextWriter。[XsltArgumentList](../../xsltargumentlist/) 提供額外的執行時參數。

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::TextWriter> &results)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | 實作 IXPathNavigable 介面的物件。它可以是 [XmlNode](../../../system.xml/xmlnode/)（通常為 [XmlDocument](../../../system.xml/xmldocument/)），或者是包含要轉換資料的 XPathDocument。 |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | 包含用於轉換之輸入的具有命名空間限定的參數的 [XsltArgumentList](../../xsltargumentlist/)。此值可以為 **nullptr**。 |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | 您想要輸出的 TextWriter。 |

## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) 方法

使用 IXPathNavigable 物件指定的輸入文件執行轉換，並將結果輸出至資料流。[XsltArgumentList](../../xsltargumentlist/) 提供額外的執行時參數。

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::Stream> &results)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | 實作 IXPathNavigable 介面的物件。它可以是 [XmlNode](../../../system.xml/xmlnode/)（通常為 [XmlDocument](../../../system.xml/xmldocument/)），或者是包含要轉換資料的 XPathDocument。 |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | 包含用於轉換之輸入的具有命名空間限定的參數的 [XsltArgumentList](../../xsltargumentlist/)。此值可以為 **nullptr**。 |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | 您想要輸出的資料流。 |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XmlWriter\>\&) 方法

使用 [XmlReader](../../../system.xml/xmlreader/) 物件指定的輸入文件執行轉換，並將結果輸出至 [XmlWriter](../../../system.xml/xmlwriter/)。

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XmlWriter> &results)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | 包含輸入文件的 [XmlReader](../../../system.xml/xmlreader/)。 |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | 您想要輸出的 [XmlWriter](../../../system.xml/xmlwriter/)。如果樣式表包含 **xsl:output** 元素，您應該使用從 [XslCompiledTransform::get_OutputSettings](../get_outputsettings/) 值返回的 [XmlWriterSettings](../../../system.xml/xmlwritersettings/) 物件建立 [XmlWriter](../../../system.xml/xmlwriter/)。這可確保 [XmlWriter](../../../system.xml/xmlwriter/) 具有正確的輸出設定。 |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) 方法

使用 [XmlReader](../../../system.xml/xmlreader/) 物件指定的輸入文件執行轉換，並將結果輸出至 [XmlWriter](../../../system.xml/xmlwriter/)。[XsltArgumentList](../../xsltargumentlist/) 提供額外的執行時參數。

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | 包含輸入文件的 [XmlReader](../../../system.xml/xmlreader/)。 |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | 包含用於轉換之輸入的具有命名空間限定的參數的 [XsltArgumentList](../../xsltargumentlist/)。此值可以為 **nullptr**。 |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | 您想要輸出的 [XmlWriter](../../../system.xml/xmlwriter/)。如果樣式表包含 **xsl:output** 元素，您應該使用從 [XslCompiledTransform::get_OutputSettings](../get_outputsettings/) 值返回的 [XmlWriterSettings](../../../system.xml/xmlwritersettings/) 物件建立 [XmlWriter](../../../system.xml/xmlwriter/)。這可確保 [XmlWriter](../../../system.xml/xmlwriter/) 具有正確的輸出設定。 |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) 方法

使用 [XmlReader](../../../system.xml/xmlreader/) 物件指定的輸入文件執行轉換，並將結果輸出至 TextWriter。[XsltArgumentList](../../xsltargumentlist/) 提供額外的執行時參數。

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::TextWriter> &results)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | 包含輸入文件的 [XmlReader](../../../system.xml/xmlreader/)。 |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | 包含用於轉換之輸入的具有命名空間限定的參數的 [XsltArgumentList](../../xsltargumentlist/)。此值可以為 **nullptr**。 |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | 您想要輸出的 TextWriter。 |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) 方法

使用 [XmlReader](../../../system.xml/xmlreader/) 物件指定的輸入文件執行轉換，並將結果輸出至資料流。[XsltArgumentList](../../xsltargumentlist/) 提供額外的執行時參數。

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::Stream> &results)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | 包含輸入文件的 [XmlReader](../../../system.xml/xmlreader/)。 |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | 包含用於轉換之輸入的具有命名空間限定的參數的 [XsltArgumentList](../../xsltargumentlist/)。此值可以為 **nullptr**。 |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | 您想要輸出的資料流。 |

## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XmlWriter\>\&) 方法

使用 URI 指定的輸入文件執行轉換，並將結果輸出至 [XmlWriter](../../../system.xml/xmlwriter/)。

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XmlWriter> &results)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | 輸入文件的 URI。 |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | 您想要輸出的 [XmlWriter](../../../system.xml/xmlwriter/)。如果樣式表包含 **xsl:output** 元素，您應該使用從 [XslCompiledTransform::get_OutputSettings](../get_outputsettings/) 值返回的 [XmlWriterSettings](../../../system.xml/xmlwritersettings/) 物件建立 [XmlWriter](../../../system.xml/xmlwriter/)。這可確保 [XmlWriter](../../../system.xml/xmlwriter/) 具有正確的輸出設定。 |

## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) 方法

使用 URI 指定的輸入文件執行轉換，並將結果輸出至 [XmlWriter](../../../system.xml/xmlwriter/)。[XsltArgumentList](../../xsltargumentlist/) 提供額外的執行時參數。

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | 輸入文件的 URI。 |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | 包含用於轉換之輸入的具有命名空間限定的參數的 [XsltArgumentList](../../xsltargumentlist/)。此值可以為 **nullptr**。 |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | 您想要輸出的 [XmlWriter](../../../system.xml/xmlwriter/)。如果樣式表包含 **xsl:output** 元素，您應該使用從 [XslCompiledTransform::get_OutputSettings](../get_outputsettings/) 值返回的 [XmlWriterSettings](../../../system.xml/xmlwritersettings/) 物件建立 [XmlWriter](../../../system.xml/xmlwriter/)。這可確保 [XmlWriter](../../../system.xml/xmlwriter/) 具有正確的輸出設定。 |

## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) 方法

使用 URI 指定的輸入文件執行轉換，並將結果輸出至 TextWriter。

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::TextWriter> &results)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | 輸入文件的 URI。 |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | 包含用於轉換之輸入的具有命名空間限定的參數的 [XsltArgumentList](../../xsltargumentlist/)。此值可以為 **nullptr**。 |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | 您想要輸出的 TextWriter。 |

## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) 方法

使用 URI 指定的輸入文件執行轉換，並將結果輸出至資料流。[XsltArgumentList](../../xsltargumentlist/) 提供額外的執行時參數。

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::Stream> &results)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | 輸入文件的 URI。 |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | 包含用於轉換之輸入的具有命名空間限定的參數的 [XsltArgumentList](../../xsltargumentlist/)。此值可以為 **nullptr**。 |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | 您想要輸出的資料流。 |

## XslCompiledTransform::Transform(const String\&, const String\&) 方法

使用 URI 指定的輸入文件執行轉換，並將結果輸出至檔案。

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const String &resultsFile)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | 輸入文件的 URI。 |
| resultsFile | const [String](../../../system/string/)\& | 輸出檔案的 URI。 |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<XmlResolver\>\&) 方法

使用 [XmlReader](../../../system.xml/xmlreader/) 物件指定的輸入文件執行轉換，並將結果輸出至 [XmlWriter](../../../system.xml/xmlwriter/)。[XsltArgumentList](../../xsltargumentlist/) 提供額外的執行時參數，而 [XmlResolver](../../../system.xml/xmlresolver/) 解析 XSLT **document()** 函數。

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results, const SharedPtr<XmlResolver> &documentResolver)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | 包含輸入文件的 [XmlReader](../../../system.xml/xmlreader/)。 |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | 包含用於轉換之輸入的具有命名空間限定的參數的 [XsltArgumentList](../../xsltargumentlist/)。此值可以為 **nullptr**。 |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | 您想要輸出的 [XmlWriter](../../../system.xml/xmlwriter/)。如果樣式表包含 **xsl:output** 元素，您應該使用從 [XslCompiledTransform::get_OutputSettings](../get_outputsettings/) 值返回的 [XmlWriterSettings](../../../system.xml/xmlwritersettings/) 物件建立 [XmlWriter](../../../system.xml/xmlwriter/)。這可確保 [XmlWriter](../../../system.xml/xmlwriter/) 具有正確的輸出設定。 |
| documentResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | 用於解析 XSLT **document()** 函數的 [XmlResolver](../../../system.xml/xmlresolver/)。如果此值為 **nullptr**，則不會解析 **document()** 函數。 |

## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<XmlResolver\>\&) 方法

使用 IXPathNavigable 物件指定的輸入文件執行轉換，並將結果輸出至 [XmlWriter](../../../system.xml/xmlwriter/)。[XsltArgumentList](../../xsltargumentlist/) 提供額外的執行時參數，而 [XmlResolver](../../../system.xml/xmlresolver/) 解析 XSLT **document()** 函數。

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results, const SharedPtr<XmlResolver> &documentResolver)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | 由 IXPathNavigable 物件指定的待轉換文件。 |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | 作為 [XsltArgumentList](../../xsltargumentlist/) 的參數清單。 |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | 您想要輸出的 [XmlWriter](../../../system.xml/xmlwriter/)。如果樣式表包含 **xsl:output** 元素，您應該使用從 [XslCompiledTransform::get_OutputSettings](../get_outputsettings/) 值返回的 [XmlWriterSettings](../../../system.xml/xmlwritersettings/) 物件建立 [XmlWriter](../../../system.xml/xmlwriter/)。這可確保 [XmlWriter](../../../system.xml/xmlwriter/) 具有正確的輸出設定。 |
| documentResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | 用於解析 XSLT **document()** 函數的 [XmlResolver](../../../system.xml/xmlresolver/)。如果此值為 **nullptr**，則不會解析 **document()** 函數。 |

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Class [XmlWriter](../../../system.xml/xmlwriter/)
* Class [XslCompiledTransform](../)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [TextWriter](../../../system.io/textwriter/)
* Class [Stream](../../../system.io/stream/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [String](../../../system/string/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)