---
title: Transform()
second_title: Aspose.Slides för C++ API-referens
description: Transformerar XML-data i XPathNavigator med de angivna argumenten och skriver ut resultatet till en XmlReader.
type: docs
weight: 40
url: /sv/system.xml.xsl/xsltransform/transform/
---
## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

Transformerar XML-data i XPathNavigator med de angivna **args** och skriver ut resultatet till en [XmlReader](../../../system.xml/xmlreader/).

```cpp
SharedPtr<XmlReader> System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | An XPathNavigator containing the data to be transformed. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | An [XsltArgumentList](../../xsltargumentlist/) containing the namespace-qualified arguments used as input to the transformation. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | The [XmlResolver](../../../system.xml/xmlresolver/) used to resolve the XSLT **document()** function. If this is **nullptr**, the **document()** function is not resolved. The [XmlResolver](../../../system.xml/xmlresolver/) is not cached after the this method completes. |

### Returvärde

Ett [XmlReader](../../../system.xml/xmlreader/) som innehåller resultatet av transformationen.

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&) method

Transformerar XML-data i XPathNavigator med de angivna **args** och skriver ut resultatet till ett [XmlReader](../../../system.xml/xmlreader/).

```cpp
SharedPtr<XmlReader> System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | An XPathNavigator containing the data to be transformed. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | An [XsltArgumentList](../../xsltargumentlist/) containing the namespace-qualified arguments used as input to the transformation. |

### Returvärde

Ett [XmlReader](../../../system.xml/xmlreader/) som innehåller resultatet av transformationen.

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

Transformerar XML-data i XPathNavigator med de angivna args och skriver ut resultatet till ett [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<XmlWriter> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | An XPathNavigator containing the data to be transformed. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | An [XsltArgumentList](../../xsltargumentlist/) containing the namespace-qualified arguments used as input to the transformation. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | The [XmlWriter](../../../system.xml/xmlwriter/) to which you want to output. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | The [XmlResolver](../../../system.xml/xmlresolver/) used to resolve the XSLT **document()** function. If this is **nullptr**, the **document()** function is not resolved. The [XmlResolver](../../../system.xml/xmlresolver/) is not cached after the this method completes. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) method

Transformerar XML-data i XPathNavigator med de angivna args och skriver ut resultatet till ett [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<XmlWriter> &output)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | An XPathNavigator containing the data to be transformed. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | An [XsltArgumentList](../../xsltargumentlist/) containing the namespace-qualified arguments used as input to the transformation. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | The [XmlWriter](../../../system.xml/xmlwriter/) to which you want to output. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

Transformerar XML-data i XPathNavigator med de angivna **args** och skriver ut resultatet till en Stream.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::Stream> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | An XPathNavigator containing the data to be transformed. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | An [XsltArgumentList](../../xsltargumentlist/) containing the namespace-qualified arguments used as input to the transformation. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | The stream to which you want to output. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | The [XmlResolver](../../../system.xml/xmlresolver/) used to resolve the XSLT **document()** function. If this is **nullptr**, the **document()** function is not resolved. The [XmlResolver](../../../system.xml/xmlresolver/) is not cached after the this method completes. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) method

Transformerar XML-data i XPathNavigator med de angivna **args** och skriver ut resultatet till en Stream.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::Stream> &output)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | An XPathNavigator containing the data to be transformed. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | An [XsltArgumentList](../../xsltargumentlist/) containing the namespace-qualified arguments used as input to the transformation. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | The stream to which you want to output. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

Transformerar XML-data i XPathNavigator med de angivna **args** och skriver ut resultatet till en TextWriter.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::TextWriter> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | An XPathNavigator containing the data to be transformed. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | An [XsltArgumentList](../../xsltargumentlist/) containing the namespace-qualified arguments used as input to the transformation. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | The TextWriter to which you want to output. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | The [XmlResolver](../../../system.xml/xmlresolver/) used to resolve the XSLT **document()** function. If this is **nullptr**, the **document()** function is not resolved. The [XmlResolver](../../../system.xml/xmlresolver/) is not cached after the this method completes. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) method

Transformerar XML-data i XPathNavigator med de angivna **args** och skriver ut resultatet till en TextWriter.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::TextWriter> &output)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | An XPathNavigator containing the data to be transformed. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | An [XsltArgumentList](../../xsltargumentlist/) containing the namespace-qualified arguments used as input to the transformation. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | The TextWriter to which you want to output. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

Transformerar XML-data i IXPathNavigable med de angivna **args** och skriver ut resultatet till en [XmlReader](../../../system.xml/xmlreader/).

```cpp
SharedPtr<XmlReader> System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | An object implementing the IXPathNavigable interface. It can be either an [XmlNode](../../../system.xml/xmlnode/) (typically an [XmlDocument](../../../system.xml/xmldocument/)), or an XPathDocument containing the data to be transformed. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | An [XsltArgumentList](../../xsltargumentlist/) containing the namespace-qualified arguments used as input to the transformation. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | The [XmlResolver](../../../system.xml/xmlresolver/) used to resolve the XSLT **document()** function. If this is **nullptr**, the **document()** function is not resolved. The [XmlResolver](../../../system.xml/xmlresolver/) is not cached after the this method completes. |

### Returvärde

Ett [XmlReader](../../../system.xml/xmlreader/) som innehåller resultatet av transformationen.

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&) method

Transformerar XML-data i IXPathNavigable med de angivna **args** och skriver ut resultatet till en [XmlReader](../../../system.xml/xmlreader/).

```cpp
SharedPtr<XmlReader> System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | An object implementing the IXPathNavigable interface. It can be either an [XmlNode](../../../system.xml/xmlnode/) (typically an [XmlDocument](../../../system.xml/xmldocument/)), or an XPathDocument containing the data to be transformed. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | An [XsltArgumentList](../../xsltargumentlist/) containing the namespace-qualified arguments used as input to the transformation. |

### Returvärde

Ett [XmlReader](../../../system.xml/xmlreader/) som innehåller resultatet av transformationen.

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

Transformerar XML-data i IXPathNavigable med de angivna **args** och skriver ut resultatet till en TextWriter.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::TextWriter> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | An object implementing the IXPathNavigable interface. It can be either an [XmlNode](../../../system.xml/xmlnode/) (typically an [XmlDocument](../../../system.xml/xmldocument/)), or an XPathDocument containing the data to be transformed. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | An [XsltArgumentList](../../xsltargumentlist/) containing the namespace-qualified arguments used as input to the transformation. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | The TextWriter to which you want to output. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | The [XmlResolver](../../../system.xml/xmlresolver/) used to resolve the XSLT **document()** function. If this is **nullptr**, the **document()** function is not resolved. The [XmlResolver](../../../system.xml/xmlresolver/) is not cached after the this method completes. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) method

Transformerar XML-data i IXPathNavigable med de angivna **args** och skriver ut resultatet till en TextWriter.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::TextWriter> &output)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | An object implementing the IXPathNavigable interface. It can be either an [XmlNode](../../../system.xml/xmlnode/) (typically an [XmlDocument](../../../system.xml/xmldocument/)), or an XPathDocument containing the data to be transformed. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | An [XsltArgumentList](../../xsltargumentlist/) containing the namespace-qualified arguments used as input to the transformation. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | The TextWriter to which you want to output. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

Transformerar XML-data i IXPathNavigable med de angivna **args** och skriver ut resultatet till en Stream.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::Stream> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | An object implementing the IXPathNavigable interface. It can be either an [XmlNode](../../../system.xml/xmlnode/) (typically an [XmlDocument](../../../system.xml/xmldocument/)), or an XPathDocument containing the data to be transformed. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | An [XsltArgumentList](../../xsltargumentlist/) containing the namespace-qualified arguments used as input to the transformation. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | The stream to which you want to output. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | The [XmlResolver](../../../system.xml/xmlresolver/) used to resolve the XSLT **document()** function. If this is **nullptr**, the **document()** function is not resolved. The [XmlResolver](../../../system.xml/xmlresolver/) is not cached after the [XslTransform::Transform](./) method completes. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) method

Transformerar XML-data i IXPathNavigable med de angivna **args** och skriver ut resultatet till en Stream.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::Stream> &output)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | An object implementing the IXPathNavigable interface. It can be either an [XmlNode](../../../system.xml/xmlnode/) (typically an [XmlDocument](../../../system.xml/xmldocument/)), or an XPathDocument containing the data to be transformed. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | An [XsltArgumentList](../../xsltargumentlist/) containing the namespace-qualified arguments used as input to the transformation. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | The stream to which you want to output. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

Transformerar XML-data i IXPathNavigable med de angivna **args** och skriver ut resultatet till en [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<XmlWriter> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | An object implementing the IXPathNavigable interface. It can be either an [XmlNode](../../../system.xml/xmlnode/) (typically an [XmlDocument](../../../system.xml/xmldocument/)), or an XPathDocument containing the data to be transformed. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | An [XsltArgumentList](../../xsltargumentlist/) containing the namespace-qualified arguments used as input to the transformation. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | The [XmlWriter](../../../system.xml/xmlwriter/) to which you want to output. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | The [XmlResolver](../../../system.xml/xmlresolver/) used to resolve the XSLT **document()** function. If this is **nullptr**, the **document()** function is not resolved. The [XmlResolver](../../../system.xml/xmlresolver/) is not cached after the this method completes. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) method

Transformerar XML-data i IXPathNavigable med de angivna **args** och skriver ut resultatet till en [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<XmlWriter> &output)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | An object implementing the IXPathNavigable interface. It can be either an [XmlNode](../../../system.xml/xmlnode/) (typically an [XmlDocument](../../../system.xml/xmldocument/)), or an XPathDocument containing the data to be transformed. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | An [XsltArgumentList](../../xsltargumentlist/) containing the namespace-qualified arguments used as input to the transformation. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | The [XmlWriter](../../../system.xml/xmlwriter/) to which you want to output. |

## XslTransform::Transform(const String\&, const String\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

Transformerar XML-data i indatafilen och skriver ut resultatet till en utdatafil.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const String &inputfile, const String &outputfile, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputfile | const [String](../../../system/string/)\& | The URL of the source document to be transformed. |
| outputfile | const [String](../../../system/string/)\& | The URL of the output file. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | The [XmlResolver](../../../system.xml/xmlresolver/) used to resolve the XSLT **document()** function. If this is **nullptr**, the **document()** function is not resolved. The [XmlResolver](../../../system.xml/xmlresolver/) is not cached after the [XslTransform::Transform](./) method completes. |

## XslTransform::Transform(const String\&, const String\&) method

Transformerar XML-data i indatafilen och skriver ut resultatet till en utdatafil.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const String &inputfile, const String &outputfile)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputfile | const [String](../../../system/string/)\& | The URL of the source document to be transformed. |
| outputfile | const [String](../../../system/string/)\& | The URL of the output file. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [XslTransform](../)
* Class [XmlWriter](../../../system.xml/xmlwriter/)
* Class [Stream](../../../system.io/stream/)
* Class [TextWriter](../../../system.io/textwriter/)
* Class [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Class [String](../../../system/string/)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)