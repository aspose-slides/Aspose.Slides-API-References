---
title: Transform()
second_title: Aspose.Slides för C++ API-referens
description: Utför transformationen med indokumentet som anges av IXPathNavigable-objektet och skriver ut resultaten till en XmlWriter.
type: docs
weight: 40
url: /sv/system.xml.xsl/xslcompiledtransform/transform/
---
## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XmlWriter\>\&) metod


Utför transformationen med indokumentet som anges av IXPathNavigable-objektet och skriver ut resultaten till en [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XmlWriter> &results)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Ett objekt som implementerar IXPathNavigable-gränssnittet. Det kan vara antingen en [XmlNode](../../../system.xml/xmlnode/) (vanligtvis en [XmlDocument](../../../system.xml/xmldocument/)) eller ett XPathDocument som innehåller data som ska transformeras. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | Den [XmlWriter](../../../system.xml/xmlwriter/) som du vill skriva ut till. Om stilmallen innehåller ett **xsl:output**-element bör du skapa [XmlWriter](../../../system.xml/xmlwriter/) med hjälp av [XmlWriterSettings](../../../system.xml/xmlwritersettings/)-objektet som returneras från [XslCompiledTransform::get_OutputSettings](../get_outputsettings/)-värdet. Detta säkerställer att [XmlWriter](../../../system.xml/xmlwriter/) har rätt utdatainställningar. |

## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) metod


Utför transformationen med indokumentet som anges av IXPathNavigable-objektet och skriver ut resultaten till en [XmlWriter](../../../system.xml/xmlwriter/). [XsltArgumentList](../../xsltargumentlist/) tillhandahåller ytterligare körargument.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Ett objekt som implementerar IXPathNavigable-gränssnittet. Det kan vara antingen en [XmlNode](../../../system.xml/xmlnode/) (vanligtvis en [XmlDocument](../../../system.xml/xmldocument/)) eller ett XPathDocument som innehåller data som ska transformeras. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | En [XsltArgumentList](../../xsltargumentlist/) som innehåller namnrymdsspecificerade argument som används som indata till transformationen. Detta värde kan vara **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | Den [XmlWriter](../../../system.xml/xmlwriter/) som du vill skriva ut till. Om stilmallen innehåller ett **xsl:output**-element bör du skapa [XmlWriter](../../../system.xml/xmlwriter/) med hjälp av [XmlWriterSettings](../../../system.xml/xmlwritersettings/)-objektet som returneras från [XslCompiledTransform::get_OutputSettings](../get_outputsettings/)-värdet. Detta säkerställer att [XmlWriter](../../../system.xml/xmlwriter/) har rätt utdatainställningar. |

## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) metod


Utför transformationen med indokumentet som anges av IXPathNavigable-objektet och skriver ut resultaten till en TextWriter. [XsltArgumentList](../../xsltargumentlist/) tillhandahåller ytterligare körargument.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::TextWriter> &results)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Ett objekt som implementerar IXPathNavigable-gränssnittet. Det kan vara antingen en [XmlNode](../../../system.xml/xmlnode/) (vanligtvis en [XmlDocument](../../../system.xml/xmldocument/)) eller ett XPathDocument som innehåller data som ska transformeras. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | En [XsltArgumentList](../../xsltargumentlist/) som innehåller namnrymdsspecificerade argument som används som indata till transformationen. Detta värde kan vara **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | TextWriter som du vill skriva ut till. |

## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) metod


Utför transformationen med indokumentet som anges av IXPathNavigable-objektet och skriver ut resultaten till en ström. [XsltArgumentList](../../xsltargumentlist/) tillhandahåller ytterligare körargument.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::Stream> &results)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Ett objekt som implementerar IXPathNavigable-gränssnittet. Det kan vara antingen en [XmlNode](../../../system.xml/xmlnode/) (vanligtvis en [XmlDocument](../../../system.xml/xmldocument/)) eller ett XPathDocument som innehåller data som ska transformeras. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | En [XsltArgumentList](../../xsltargumentlist/) som innehåller namnrymdsspecificerade argument som används som indata till transformationen. Detta värde kan vara **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Strömmen som du vill skriva ut till. |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XmlWriter\>\&) metod


Utför transformationen med indokumentet som anges av [XmlReader](../../../system.xml/xmlreader/)-objektet och skriver ut resultaten till en [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XmlWriter> &results)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Den [XmlReader](../../../system.xml/xmlreader/) som innehåller indokumentet. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | Den [XmlWriter](../../../system.xml/xmlwriter/) som du vill skriva ut till. Om stilmallen innehåller ett **xsl:output**-element bör du skapa [XmlWriter](../../../system.xml/xmlwriter/) med hjälp av [XmlWriterSettings](../../../system.xml/xmlwritersettings/)-objektet som returneras från [XslCompiledTransform::get_OutputSettings](../get_outputsettings/)-värdet. Detta säkerställer att [XmlWriter](../../../system.xml/xmlwriter/) har rätt utdatainställningar. |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) metod


Utför transformationen med indokumentet som anges av [XmlReader](../../../system.xml/xmlreader/)-objektet och skriver ut resultaten till en [XmlWriter](../../../system.xml/xmlwriter/). [XsltArgumentList](../../xsltargumentlist/) tillhandahåller ytterligare körargument.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Ett [XmlReader](../../../system.xml/xmlreader/) som innehåller indokumentet. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | En [XsltArgumentList](../../xsltargumentlist/) som innehåller namnrymdsspecificerade argument som används som indata till transformationen. Detta värde kan vara **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | Den [XmlWriter](../../../system.xml/xmlwriter/) som du vill skriva ut till. Om stilmallen innehåller ett **xsl:output**-element bör du skapa [XmlWriter](../../../system.xml/xmlwriter/) med hjälp av [XmlWriterSettings](../../../system.xml/xmlwritersettings/)-objektet som returneras från [XslCompiledTransform::get_OutputSettings](../get_outputsettings/)-värdet. Detta säkerställer att [XmlWriter](../../../system.xml/xmlwriter/) har rätt utdatainställningar. |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) metod


Utför transformationen med indokumentet som anges av [XmlReader](../../../system.xml/xmlreader/)-objektet och skriver ut resultaten till en TextWriter. [XsltArgumentList](../../xsltargumentlist/) tillhandahåller ytterligare körargument.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::TextWriter> &results)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Ett [XmlReader](../../../system.xml/xmlreader/) som innehåller indokumentet. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | En [XsltArgumentList](../../xsltargumentlist/) som innehåller namnrymdsspecificerade argument som används som indata till transformationen. Detta värde kan vara **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | TextWriter som du vill skriva ut till. |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) metod


Utför transformationen med indokumentet som anges av [XmlReader](../../../system.xml/xmlreader/)-objektet och skriver ut resultaten till en ström. [XsltArgumentList](../../xsltargumentlist/) tillhandahåller ytterligare körargument.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::Stream> &results)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Ett [XmlReader](../../../system.xml/xmlreader/) som innehåller indokumentet. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | En [XsltArgumentList](../../xsltargumentlist/) som innehåller namnrymdsspecificerade argument som används som indata till transformationen. Detta värde kan vara **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Strömmen som du vill skriva ut till. |

## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XmlWriter\>\&) metod


Utför transformationen med indokumentet som anges av URI:n och skriver ut resultaten till en [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XmlWriter> &results)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | URI:n för indokumentet. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | Den [XmlWriter](../../../system.xml/xmlwriter/) som du vill skriva ut till. Om stilmallen innehåller ett **xsl:output**-element bör du skapa [XmlWriter](../../../system.xml/xmlwriter/) med hjälp av [XmlWriterSettings](../../../system.xml/xmlwritersettings/)-objektet som returneras från [XslCompiledTransform::get_OutputSettings](../get_outputsettings/)-värdet. Detta säkerställer att [XmlWriter](../../../system.xml/xmlwriter/) har rätt utdatainställningar. |

## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) metod


Utför transformationen med indokumentet som anges av URI:n och skriver ut resultaten till en [XmlWriter](../../../system.xml/xmlwriter/). [XsltArgumentList](../../xsltargumentlist/) tillhandahåller ytterligare körargument.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | URI:n för indokumentet. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | En [XsltArgumentList](../../xsltargumentlist/) som innehåller namnrymdsspecificerade argument som används som indata till transformationen. Detta värde kan vara **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | Den [XmlWriter](../../../system.xml/xmlwriter/) som du vill skriva ut till. Om stilmallen innehåller ett **xsl:output**-element bör du skapa [XmlWriter](../../../system.xml/xmlwriter/) med hjälp av [XmlWriterSettings](../../../system.xml/xmlwritersettings/)-objektet som returneras från [XslCompiledTransform::get_OutputSettings](../get_outputsettings/)-värdet. Detta säkerställer att [XmlWriter](../../../system.xml/xmlwriter/) har rätt utdatainställningar. |

## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) metod


Utför transformationen med indokumentet som anges av URI:n och skriver ut resultaten till en TextWriter.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::TextWriter> &results)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | URI:n för indokumentet. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | En [XsltArgumentList](../../xsltargumentlist/) som innehåller namnrymdsspecificerade argument som används som indata till transformationen. Detta värde kan vara **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | TextWriter som du vill skriva ut till. |

## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) metod


Utför transformationen med indokumentet som anges av URI:n och skriver ut resultaten till en ström. [XsltArgumentList](../../xsltargumentlist/) tillhandahåller ytterligare körargument.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::Stream> &results)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | URI:n för indokumentet. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | En [XsltArgumentList](../../xsltargumentlist/) som innehåller namnrymdsspecificerade argument som används som indata till transformationen. Detta värde kan vara **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Strömmen som du vill skriva ut till. |

## XslCompiledTransform::Transform(const String\&, const String\&) metod


Utför transformationen med indokumentet som anges av URI:n och skriver ut resultaten till en fil.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const String &resultsFile)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | URI:n för indokumentet. |
| resultsFile | const [String](../../../system/string/)\& | URI:n för utdatafilen. |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<XmlResolver\>\&) metod


Utför transformationen med indokumentet som anges av [XmlReader](../../../system.xml/xmlreader/)-objektet och skriver ut resultaten till en [XmlWriter](../../../system.xml/xmlwriter/). [XsltArgumentList](../../xsltargumentlist/) tillhandahåller ytterligare körargument och [XmlResolver](../../../system.xml/xmlresolver/) löser XSLT **document()**-funktionen.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results, const SharedPtr<XmlResolver> &documentResolver)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Ett [XmlReader](../../../system.xml/xmlreader/) som innehåller indokumentet. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | En [XsltArgumentList](../../xsltargumentlist/) som innehåller namnrymdsspecificerade argument som används som indata till transformationen. Detta värde kan vara **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | Den [XmlWriter](../../../system.xml/xmlwriter/) som du vill skriva ut till. Om stilmallen innehåller ett **xsl:output**-element bör du skapa [XmlWriter](../../../system.xml/xmlwriter/) med hjälp av [XmlWriterSettings](../../../system.xml/xmlwritersettings/)-objektet som returneras från [XslCompiledTransform::get_OutputSettings](../get_outputsettings/)-värdet. Detta säkerställer att [XmlWriter](../../../system.xml/xmlwriter/) har rätt utdatainställningar. |
| documentResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | Den [XmlResolver](../../../system.xml/xmlresolver/) som används för att lösa XSLT **document()**-funktionen. Om detta är **nullptr** löses inte **document()**-funktionen. |

## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<XmlResolver\>\&) metod


Utför transformationen med indokumentet som anges av IXPathNavigable-objektet och skriver ut resultaten till en [XmlWriter](../../../system.xml/xmlwriter/). [XsltArgumentList](../../xsltargumentlist/) tillhandahåller ytterligare körargument och [XmlResolver](../../../system.xml/xmlresolver/) löser XSLT **document()**-funktionen.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results, const SharedPtr<XmlResolver> &documentResolver)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Dokumentet som ska transformeras och som anges av IXPathNavigable-objektet. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Argumentlista som [XsltArgumentList](../../xsltargumentlist/). |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | Den [XmlWriter](../../../system.xml/xmlwriter/) som du vill skriva ut till. Om stilmallen innehåller ett **xsl:output**-element bör du skapa [XmlWriter](../../../system.xml/xmlwriter/) genom att använda [XmlWriterSettings](../../../system.xml/xmlwritersettings/)-objektet som returneras från [XslCompiledTransform::get_OutputSettings](../get_outputsettings/)-värdet. Detta säkerställer att [XmlWriter](../../../system.xml/xmlwriter/) har rätt utdatainställningar. |
| documentResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | Den [XmlResolver](../../../system.xml/xmlresolver/) som används för att lösa XSLT **document()**-funktionen. Om detta är **nullptr** löses inte **document()**-funktionen. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Klass [XmlWriter](../../../system.xml/xmlwriter/)
* Klass [XslCompiledTransform](../)
* Klass [XsltArgumentList](../../xsltargumentlist/)
* Klass [TextWriter](../../../system.io/textwriter/)
* Klass [Stream](../../../system.io/stream/)
* Klass [XmlReader](../../../system.xml/xmlreader/)
* Klass [String](../../../system/string/)
* Klass [XmlResolver](../../../system.xml/xmlresolver/)
* Namnrymd [System::Xml::Xsl](../../)
* Bibliotek [Aspose.Slides](../../../)