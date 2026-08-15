---
title: Transform()
second_title: Aspose.Slides for C++ API 參考文件
description: 使用指定的 args 轉換 XPathNavigator 中的 XML 資料，並將結果輸出至 XmlReader。
type: docs
weight: 40
url: /zh-hant/system.xml.xsl/xsltransform/transform/
---
## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) 方法

使用指定的 **args** 轉換 XPathNavigator 中的 XML 資料，並將結果輸出至 [XmlReader](../../../system.xml/xmlreader/)。

```cpp
SharedPtr<XmlReader> System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | 包含要轉換資料的 XPathNavigator。 |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | 包含用作轉換輸入之具名稱空間限定參數的 [XsltArgumentList](../../xsltargumentlist/)。 |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | 用於解析 XSLT **document()** 函式的 [XmlResolver](../../../system.xml/xmlresolver/)。如果此值為 **nullptr**，則不會解析 **document()** 函式。此 [XmlResolver](../../../system.xml/xmlresolver/) 在本方法完成後不會被快取。 |

### 傳回值

包含轉換結果的 [XmlReader](../../../system.xml/xmlreader/)。

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&) 方法

使用指定的 **args** 轉換 XPathNavigator 中的 XML 資料，並將結果輸出至 [XmlReader](../../../system.xml/xmlreader/)。

```cpp
SharedPtr<XmlReader> System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | 包含要轉換資料的 XPathNavigator。 |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) 包含用作轉換輸入之具名稱空間限定參數。 |

### 傳回值

包含轉換結果的 [XmlReader](../../../system.xml/xmlreader/)。

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) 方法

使用指定的 args 轉換 XPathNavigator 中的 XML 資料，並將結果輸出至 [XmlWriter](../../../system.xml/xmlwriter/)。

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<XmlWriter> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | 包含要轉換資料的 XPathNavigator。 |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) 包含用作轉換輸入之具名稱空間限定參數。 |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | 您想要輸出的 [XmlWriter](../../../system.xml/xmlwriter/)。 |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | 用於解析 XSLT **document()** 函式的 [XmlResolver](../../../system.xml/xmlresolver/)。如果此值為 **nullptr**，則不會解析 **document()** 函式。此 [XmlResolver](../../../system.xml/xmlresolver/) 在本方法完成後不會被快取。 |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) 方法

使用指定的 args 轉換 XPathNavigator 中的 XML 資料，並將結果輸出至 [XmlWriter](../../../system.xml/xmlwriter/)。

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<XmlWriter> &output)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | 包含要轉換資料的 XPathNavigator。 |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) 包含用作轉換輸入之具名稱空間限定參數。 |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | 您想要輸出的 [XmlWriter](../../../system.xml/xmlwriter/)。 |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) 方法

使用指定的 **args** 轉換 XPathNavigator 中的 XML 資料，並將結果輸出至 Stream。

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::Stream> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | 包含要轉換資料的 XPathNavigator。 |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) 包含用作轉換輸入之具名稱空間限定參數。 |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | 您想要輸出的串流。 |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | 用於解析 XSLT **document()** 函式的 [XmlResolver](../../../system.xml/xmlresolver/)。如果此值為 **nullptr**，則不會解析 **document()** 函式。此 [XmlResolver](../../../system.xml/xmlresolver/) 在本方法完成後不會被快取。 |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) 方法

使用指定的 **args** 轉換 XPathNavigator 中的 XML 資料，並將結果輸出至 Stream。

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::Stream> &output)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | 包含要轉換資料的 XPathNavigator。 |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) 包含用作轉換輸入之具名稱空間限定參數。 |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | 您想要輸出的串流。 |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) 方法

使用指定的 **args** 轉換 XPathNavigator 中的 XML 資料，並將結果輸出至 TextWriter。

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::TextWriter> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | 包含要轉換資料的 XPathNavigator。 |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) 包含用作轉換輸入之具名稱空間限定參數。 |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | 您想要輸出的 TextWriter。 |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | 用於解析 XSLT **document()** 函式的 [XmlResolver](../../../system.xml/xmlresolver/)。如果此值為 **nullptr**，則不會解析 **document()** 函式。此 [XmlResolver](../../../system.xml/xmlresolver/) 在本方法完成後不會被快取。 |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) 方法

使用指定的 **args** 轉換 XPathNavigator 中的 XML 資料，並將結果輸出至 TextWriter。

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::TextWriter> &output)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | 包含要轉換資料的 XPathNavigator。 |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) 包含用作轉換輸入之具名稱空間限定參數。 |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | 您想要輸出的 TextWriter。 |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) 方法

使用指定的 **args** 轉換 IXPathNavigable 中的 XML 資料，並將結果輸出至 [XmlReader](../../../system.xml/xmlreader/)。

```cpp
SharedPtr<XmlReader> System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | 實作 IXPathNavigable 介面的物件。它可以是 [XmlNode](../../../system.xml/xmlnode/) (通常是 [XmlDocument](../../../system.xml/xmldocument/))，或是包含要轉換資料的 XPathDocument。 |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) 包含用作轉換輸入之具名稱空間限定參數。 |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | 用於解析 XSLT **document()** 函式的 [XmlResolver](../../../system.xml/xmlresolver/)。如果此值為 **nullptr**，則不會解析 **document()** 函式。此 [XmlResolver](../../../system.xml/xmlresolver/) 在本方法完成後不會被快取。 |

### 傳回值

包含轉換結果的 [XmlReader](../../../system.xml/xmlreader/)。

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&) 方法

使用指定的 **args** 轉換 IXPathNavigable 中的 XML 資料，並將結果輸出至 [XmlReader](../../../system.xml/xmlreader/)。

```cpp
SharedPtr<XmlReader> System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | 實作 IXPathNavigable 介面的物件。它可以是 [XmlNode](../../../system.xml/xmlnode/) (通常是 [XmlDocument](../../../system.xml/xmldocument/))，或是包含要轉換資料的 XPathDocument。 |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) 包含用作轉換輸入之具名稱空間限定參數。 |

### 傳回值

包含轉換結果的 [XmlReader](../../../system.xml/xmlreader/)。

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) 方法

使用指定的 **args** 轉換 IXPathNavigable 中的 XML 資料，並將結果輸出至 TextWriter。

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::TextWriter> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | 實作 IXPathNavigable 介面的物件。它可以是 [XmlNode](../../../system.xml/xmlnode/) (通常是 [XmlDocument](../../../system.xml/xmldocument/))，或是包含要轉換資料的 XPathDocument。 |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) 包含用作轉換輸入之具名稱空間限定參數。 |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | 您想要輸出的 TextWriter。 |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | 用於解析 XSLT **document()** 函式的 [XmlResolver](../../../system.xml/xmlresolver/)。如果此值為 **nullptr**，則不會解析 **document()** 函式。此 [XmlResolver](../../../system.xml/xmlresolver/) 在本方法完成後不會被快取。 |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) 方法

使用指定的 **args** 轉換 IXPathNavigable 中的 XML 資料，並將結果輸出至 TextWriter。

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::TextWriter> &output)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | 實作 IXPathNavigable 介面的物件。它可以是 [XmlNode](../../../system.xml/xmlnode/) (通常是 [XmlDocument](../../../system.xml/xmldocument/))，或是包含要轉換資料的 XPathDocument。 |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) 包含用作轉換輸入之具名稱空間限定參數。 |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | 您想要輸出的 TextWriter。 |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) 方法

使用指定的 **args** 轉換 IXPathNavigable 中的 XML 資料，並將結果輸出至 Stream。

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::Stream> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | 實作 IXPathNavigable 介面的物件。它可以是 [XmlNode](../../../system.xml/xmlnode/) (通常是 [XmlDocument](../../../system.xml/xmldocument/))，或是包含要轉換資料的 XPathDocument。 |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) 包含用作轉換輸入之具名稱空間限定參數。 |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | 您想要輸出的串流。 |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | 用於解析 XSLT **document()** 函式的 [XmlResolver](../../../system.xml/xmlresolver/)。如果此值為 **nullptr**，則不會解析 **document()** 函式。此 [XmlResolver](../../../system.xml/xmlresolver/) 在 [XslTransform::Transform](./) 方法完成後不會被快取。 |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) 方法

使用指定的 **args** 轉換 IXPathNavigable 中的 XML 資料，並將結果輸出至 Stream。

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::Stream> &output)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | 實作 IXPathNavigable 介面的物件。它可以是 [XmlNode](../../../system.xml/xmlnode/) (通常是 [XmlDocument](../../../system.xml/xmldocument/))，或是包含要轉換資料的 XPathDocument。 |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) 包含用作轉換輸入之具名稱空間限定參數。 |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | 您想要輸出的串流。 |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) 方法

使用指定的 **args** 轉換 IXPathNavigable 中的 XML 資料，並將結果輸出至 [XmlWriter](../../../system.xml/xmlwriter/)。

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<XmlWriter> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | 實作 IXPathNavigable 介面的物件。它可以是 [XmlNode](../../../system.xml/xmlnode/) (通常是 [XmlDocument](../../../system.xml/xmldocument/))，或是包含要轉換資料的 XPathDocument。 |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) 包含用作轉換輸入之具名稱空間限定參數。 |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | 您想要輸出的 [XmlWriter](../../../system.xml/xmlwriter/)。 |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | 用於解析 XSLT **document()** 函式的 [XmlResolver](../../../system.xml/xmlresolver/)。如果此值為 **nullptr**，則不會解析 **document()** 函式。此 [XmlResolver](../../../system.xml/xmlresolver/) 在本方法完成後不會被快取。 |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) 方法

使用指定的 **args** 轉換 IXPathNavigable 中的 XML 資料，並將結果輸出至 [XmlWriter](../../../system.xml/xmlwriter/)。

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<XmlWriter> &output)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | 實作 IXPathNavigable 介面的物件。它可以是 [XmlNode](../../../system.xml/xmlnode/) (通常是 [XmlDocument](../../../system.xml/xmldocument/))，或是包含要轉換資料的 XPathDocument。 |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) 包含用作轉換輸入之具名稱空間限定參數。 |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | 您想要輸出的 [XmlWriter](../../../system.xml/xmlwriter/)。 |

## XslTransform::Transform(const String\&, const String\&, const SharedPtr\<System::Xml::XmlResolver\>\&) 方法

轉換輸入檔案中的 XML 資料，並將結果輸出至輸出檔案。

```cpp
void System::Xml::Xsl::XslTransform::Transform(const String &inputfile, const String &outputfile, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| inputfile | const [String](../../../system/string/)\& | 要轉換的來源文件的 URL。 |
| outputfile | const [String](../../../system/string/)\& | 輸出文件的 URL。 |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | 用於解析 XSLT **document()** 函式的 [XmlResolver](../../../system.xml/xmlresolver/)。如果此值為 **nullptr**，則不會解析 **document()** 函式。此 [XmlResolver](../../../system.xml/xmlresolver/) 在 [XslTransform::Transform](./) 方法完成後不會被快取。 |

## XslTransform::Transform(const String\&, const String\&) 方法

轉換輸入檔案中的 XML 資料，並將結果輸出至輸出檔案。

```cpp
void System::Xml::Xsl::XslTransform::Transform(const String &inputfile, const String &outputfile)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| inputfile | const [String](../../../system/string/)\& | 要轉換的來源文件的 URL。 |
| outputfile | const [String](../../../system/string/)\& | 輸出文件的 URL。 |

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [XmlReader](../../../system.xml/xmlreader/)
* 類別 [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* 類別 [XsltArgumentList](../../xsltargumentlist/)
* 類別 [XmlResolver](../../../system.xml/xmlresolver/)
* 類別 [XslTransform](../)
* 類別 [XmlWriter](../../../system.xml/xmlwriter/)
* 類別 [Stream](../../../system.io/stream/)
* 類別 [TextWriter](../../../system.io/textwriter/)
* 類別 [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* 類別 [String](../../../system/string/)
* 命名空間 [System::Xml::Xsl](../../)
* 函式庫 [Aspose.Slides](../../../)