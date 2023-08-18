---
title: Transform()
second_title: Aspose.Slides for C++ API Reference
description: Executes the transform using the input document specified by the IXPathNavigable object and outputs the results to an XmlWriter.
type: docs
weight: 40
url: /system.xml.xsl/xslcompiledtransform/transform/
---
## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XmlWriter\>\&) method


Executes the transform using the input document specified by the IXPathNavigable object and outputs the results to an [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XmlWriter> &results)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | An object implementing the IXPathNavigable interface. It can be either an [XmlNode](../../../system.xml/xmlnode/) (typically an [XmlDocument](../../../system.xml/xmldocument/)), or an XPathDocument containing the data to be transformed. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | The [XmlWriter](../../../system.xml/xmlwriter/) to which you want to output. If the style sheet contains an **xsl:output** element, you should create the [XmlWriter](../../../system.xml/xmlwriter/) using the [XmlWriterSettings](../../../system.xml/xmlwritersettings/) object returned from the [XslCompiledTransform::get_OutputSettings](../get_outputsettings/) value. This ensures that the [XmlWriter](../../../system.xml/xmlwriter/) has the correct output settings. |

## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) method


Executes the transform using the input document specified by the IXPathNavigable object and outputs the results to an [XmlWriter](../../../system.xml/xmlwriter/). The [XsltArgumentList](../../xsltargumentlist/) provides additional run-time arguments.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | An object implementing the IXPathNavigable interface. It can be either an [XmlNode](../../../system.xml/xmlnode/) (typically an [XmlDocument](../../../system.xml/xmldocument/)), or an XPathDocument containing the data to be transformed. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | An [XsltArgumentList](../../xsltargumentlist/) containing the namespace-qualified arguments used as input to the transform. This value can be **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | The [XmlWriter](../../../system.xml/xmlwriter/) to which you want to output. If the style sheet contains an **xsl:output** element, you should create the [XmlWriter](../../../system.xml/xmlwriter/) using the [XmlWriterSettings](../../../system.xml/xmlwritersettings/) object returned from the [XslCompiledTransform::get_OutputSettings](../get_outputsettings/) value. This ensures that the [XmlWriter](../../../system.xml/xmlwriter/) has the correct output settings. |

## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) method


Executes the transform using the input document specified by the IXPathNavigable object and outputs the results to an TextWriter. The [XsltArgumentList](../../xsltargumentlist/) provides additional run-time arguments.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::TextWriter> &results)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | An object implementing the IXPathNavigable interface. It can be either an [XmlNode](../../../system.xml/xmlnode/) (typically an [XmlDocument](../../../system.xml/xmldocument/)), or an XPathDocument containing the data to be transformed. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | An [XsltArgumentList](../../xsltargumentlist/) containing the namespace-qualified arguments used as input to the transform. This value can be **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | The TextWriter to which you want to output. |

## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) method


Executes the transform using the input document specified by the IXPathNavigable object and outputs the results to a stream. The [XsltArgumentList](../../xsltargumentlist/) provides additional runtime arguments.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::Stream> &results)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | An object implementing the IXPathNavigable interface. It can be either an [XmlNode](../../../system.xml/xmlnode/) (typically an [XmlDocument](../../../system.xml/xmldocument/)), or an XPathDocument containing the data to be transformed. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | An [XsltArgumentList](../../xsltargumentlist/) containing the namespace-qualified arguments used as input to the transform. This value can be **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | The stream to which you want to output. |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XmlWriter\>\&) method


Executes the transform using the input document specified by the [XmlReader](../../../system.xml/xmlreader/) object and outputs the results to an [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XmlWriter> &results)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | The [XmlReader](../../../system.xml/xmlreader/) containing the input document. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | The [XmlWriter](../../../system.xml/xmlwriter/) to which you want to output. If the style sheet contains an **xsl:output** element, you should create the [XmlWriter](../../../system.xml/xmlwriter/) using the [XmlWriterSettings](../../../system.xml/xmlwritersettings/) object returned from the [XslCompiledTransform::get_OutputSettings](../get_outputsettings/) value. This ensures that the [XmlWriter](../../../system.xml/xmlwriter/) has the correct output settings. |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) method


Executes the transform using the input document specified by the [XmlReader](../../../system.xml/xmlreader/) object and outputs the results to an [XmlWriter](../../../system.xml/xmlwriter/). The [XsltArgumentList](../../xsltargumentlist/) provides additional run-time arguments.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | An [XmlReader](../../../system.xml/xmlreader/) containing the input document. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | An [XsltArgumentList](../../xsltargumentlist/) containing the namespace-qualified arguments used as input to the transform. This value can be **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | The [XmlWriter](../../../system.xml/xmlwriter/) to which you want to output. If the style sheet contains an **xsl:output** element, you should create the [XmlWriter](../../../system.xml/xmlwriter/) using the [XmlWriterSettings](../../../system.xml/xmlwritersettings/) object returned from the [XslCompiledTransform::get_OutputSettings](../get_outputsettings/) value. This ensures that the [XmlWriter](../../../system.xml/xmlwriter/) has the correct output settings. |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) method


Executes the transform using the input document specified by the [XmlReader](../../../system.xml/xmlreader/) object and outputs the results to a TextWriter. The [XsltArgumentList](../../xsltargumentlist/) provides additional run-time arguments.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::TextWriter> &results)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | An [XmlReader](../../../system.xml/xmlreader/) containing the input document. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | An [XsltArgumentList](../../xsltargumentlist/) containing the namespace-qualified arguments used as input to the transform. This value can be **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | The TextWriter to which you want to output. |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) method


Executes the transform using the input document specified by the [XmlReader](../../../system.xml/xmlreader/) object and outputs the results to a stream. The [XsltArgumentList](../../xsltargumentlist/) provides additional run-time arguments.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::Stream> &results)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | An [XmlReader](../../../system.xml/xmlreader/) containing the input document. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | An [XsltArgumentList](../../xsltargumentlist/) containing the namespace-qualified arguments used as input to the transform. This value can be **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | The stream to which you want to output. |

## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XmlWriter\>\&) method


Executes the transform using the input document specified by the URI and outputs the results to an [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XmlWriter> &results)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | The URI of the input document. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | The [XmlWriter](../../../system.xml/xmlwriter/) to which you want to output. If the style sheet contains an **xsl:output** element, you should create the [XmlWriter](../../../system.xml/xmlwriter/) using the [XmlWriterSettings](../../../system.xml/xmlwritersettings/) object returned from the [XslCompiledTransform::get_OutputSettings](../get_outputsettings/) value. This ensures that the [XmlWriter](../../../system.xml/xmlwriter/) has the correct output settings. |

## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) method


Executes the transform using the input document specified by the URI and outputs the results to an [XmlWriter](../../../system.xml/xmlwriter/). The [XsltArgumentList](../../xsltargumentlist/) provides additional run-time arguments.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | The URI of the input document. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | An [XsltArgumentList](../../xsltargumentlist/) containing the namespace-qualified arguments used as input to the transform. This value can be **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | The [XmlWriter](../../../system.xml/xmlwriter/) to which you want to output. If the style sheet contains an **xsl:output** element, you should create the [XmlWriter](../../../system.xml/xmlwriter/) using the [XmlWriterSettings](../../../system.xml/xmlwritersettings/) object returned from the [XslCompiledTransform::get_OutputSettings](../get_outputsettings/) value. This ensures that the [XmlWriter](../../../system.xml/xmlwriter/) has the correct output settings. |

## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) method


Executes the transform using the input document specified by the URI and outputs the results to a TextWriter.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::TextWriter> &results)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | The URI of the input document. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | An [XsltArgumentList](../../xsltargumentlist/) containing the namespace-qualified arguments used as input to the transform. This value can be **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | The TextWriter to which you want to output. |

## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) method


Executes the transform using the input document specified by the URI and outputs the results to stream. The [XsltArgumentList](../../xsltargumentlist/) provides additional run-time arguments.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::Stream> &results)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | The URI of the input document. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | An [XsltArgumentList](../../xsltargumentlist/) containing the namespace-qualified arguments used as input to the transform. This value can be **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | The stream to which you want to output. |

## XslCompiledTransform::Transform(const String\&, const String\&) method


Executes the transform using the input document specified by the URI and outputs the results to a file.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const String &resultsFile)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | The URI of the input document. |
| resultsFile | const [String](../../../system/string/)\& | The URI of the output file. |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<XmlResolver\>\&) method


Executes the transform using the input document specified by the [XmlReader](../../../system.xml/xmlreader/) object and outputs the results to an [XmlWriter](../../../system.xml/xmlwriter/). The [XsltArgumentList](../../xsltargumentlist/) provides additional run-time arguments and the [XmlResolver](../../../system.xml/xmlresolver/) resolves the XSLT **document()** function.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results, const SharedPtr<XmlResolver> &documentResolver)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | An [XmlReader](../../../system.xml/xmlreader/) containing the input document. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | An [XsltArgumentList](../../xsltargumentlist/) containing the namespace-qualified arguments used as input to the transform. This value can be **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | The [XmlWriter](../../../system.xml/xmlwriter/) to which you want to output. If the style sheet contains an **xsl:output** element, you should create the [XmlWriter](../../../system.xml/xmlwriter/) using the [XmlWriterSettings](../../../system.xml/xmlwritersettings/) object returned from the [XslCompiledTransform::get_OutputSettings](../get_outputsettings/) value. This ensures that the [XmlWriter](../../../system.xml/xmlwriter/) has the correct output settings. |
| documentResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | The [XmlResolver](../../../system.xml/xmlresolver/) used to resolve the XSLT **document()** function. If this is **nullptr**, the **document()** function is not resolved. |

## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<XmlResolver\>\&) method


Executes the transform by using the input document that is specified by the IXPathNavigable object and outputs the results to an [XmlWriter](../../../system.xml/xmlwriter/). The [XsltArgumentList](../../xsltargumentlist/) provides additional run-time arguments and the [XmlResolver](../../../system.xml/xmlresolver/) resolves the XSLT **document()** function.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results, const SharedPtr<XmlResolver> &documentResolver)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | The document to transform that is specified by the IXPathNavigable object. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Argument list as [XsltArgumentList](../../xsltargumentlist/). |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | The [XmlWriter](../../../system.xml/xmlwriter/) to which you want to output. If the style sheet contains an **xsl:output** element, you should create the [XmlWriter](../../../system.xml/xmlwriter/) by using the [XmlWriterSettings](../../../system.xml/xmlwritersettings/) object that is returned from the [XslCompiledTransform::get_OutputSettings](../get_outputsettings/) value. This ensures that the [XmlWriter](../../../system.xml/xmlwriter/) has the correct output settings. |
| documentResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | The [XmlResolver](../../../system.xml/xmlresolver/) used to resolve the XSLT **document()** function. If this is **nullptr**, the **document()** function is not resolved. |

## See Also

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