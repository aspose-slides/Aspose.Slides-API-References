---
title: Transform()
second_title: Aspose.Slides für C++ API-Referenz
description: Transformiert die XML-Daten im XPathNavigator mithilfe der angegebenen args und gibt das Ergebnis an einen XmlReader aus.
type: docs
weight: 40
url: /de/system.xml.xsl/xsltransform/transform/
---
## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) Methode

Transformiert die XML-Daten im XPathNavigator mithilfe der angegebenen **args** und gibt das Ergebnis an ein [XmlReader](../../../system.xml/xmlreader/) aus.

```cpp
SharedPtr<XmlReader> System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Ein XPathNavigator, der die zu transformierenden Daten enthält. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Ein [XsltArgumentList](../../xsltargumentlist/), der die namensraumqualifizierten Argumente enthält, die als Eingabe für die Transformation verwendet werden. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | Der [XmlResolver](../../../system.xml/xmlresolver/), der verwendet wird, um die XSLT **document()**-Funktion aufzulösen. Wenn dies **nullptr** ist, wird die **document()**-Funktion nicht aufgelöst. Der [XmlResolver](../../../system.xml/xmlresolver/) wird nach Abschluss dieser Methode nicht zwischengespeichert. |

### Rückgabewert

Ein [XmlReader](../../../system.xml/xmlreader/) mit den Ergebnissen der Transformation.

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&) Methode

Transformiert die XML-Daten im XPathNavigator mithilfe der angegebenen **args** und gibt das Ergebnis an ein [XmlReader](../../../system.xml/xmlreader/) aus.

```cpp
SharedPtr<XmlReader> System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Ein XPathNavigator, der die zu transformierenden Daten enthält. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Ein [XsltArgumentList](../../xsltargumentlist/), der die namensraumqualifizierten Argumente enthält, die als Eingabe für die Transformation verwendet werden. |

### Rückgabewert

Ein [XmlReader](../../../system.xml/xmlreader/) mit den Ergebnissen der Transformation.

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) Methode

Transformiert die XML-Daten im XPathNavigator mithilfe der angegebenen args und gibt das Ergebnis an ein [XmlWriter](../../../system.xml/xmlwriter/) aus.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<XmlWriter> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Ein XPathNavigator, der die zu transformierenden Daten enthält. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Ein [XsltArgumentList](../../xsltargumentlist/), der die namensraumqualifizierten Argumente enthält, die als Eingabe für die Transformation verwendet werden. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | Der [XmlWriter](../../../system.xml/xmlwriter/), in den Sie ausgeben möchten. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | Der [XmlResolver](../../../system.xml/xmlresolver/), der verwendet wird, um die XSLT **document()**-Funktion aufzulösen. Wenn dies **nullptr** ist, wird die **document()**-Funktion nicht aufgelöst. Der [XmlResolver](../../../system.xml/xmlresolver/) wird nach Abschluss dieser Methode nicht zwischengespeichert. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) Methode

Transformiert die XML-Daten im XPathNavigator mithilfe der angegebenen args und gibt das Ergebnis an ein [XmlWriter](../../../system.xml/xmlwriter/) aus.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<XmlWriter> &output)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Ein XPathNavigator, der die zu transformierenden Daten enthält. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Ein [XsltArgumentList](../../xsltargumentlist/), der die namensraumqualifizierten Argumente enthält, die als Eingabe für die Transformation verwendet werden. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | Der [XmlWriter](../../../system.xml/xmlwriter/), in den Sie ausgeben möchten. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) Methode

Transformiert die XML-Daten im XPathNavigator mithilfe der angegebenen **args** und gibt das Ergebnis an einen Stream aus.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::Stream> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Ein XPathNavigator, der die zu transformierenden Daten enthält. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Ein [XsltArgumentList](../../xsltargumentlist/), der die namensraumqualifizierten Argumente enthält, die als Eingabe für die Transformation verwendet werden. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Der Stream, in den Sie ausgeben möchten. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | Der [XmlResolver](../../../system.xml/xmlresolver/), der verwendet wird, um die XSLT **document()**-Funktion aufzulösen. Wenn dies **nullptr** ist, wird die **document()**-Funktion nicht aufgelöst. Der [XmlResolver](../../../system.xml/xmlresolver/) wird nach Abschluss dieser Methode nicht zwischengespeichert. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) Methode

Transformiert die XML-Daten im XPathNavigator mithilfe der angegebenen **args** und gibt das Ergebnis an einen Stream aus.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::Stream> &output)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Ein XPathNavigator, der die zu transformierenden Daten enthält. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Ein [XsltArgumentList](../../xsltargumentlist/), der die namensraumqualifizierten Argumente enthält, die als Eingabe für die Transformation verwendet werden. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Der Stream, in den Sie ausgeben möchten. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) Methode

Transformiert die XML-Daten im XPathNavigator mithilfe der angegebenen **args** und gibt das Ergebnis an einen TextWriter aus.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::TextWriter> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Ein XPathNavigator, der die zu transformierenden Daten enthält. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Ein [XsltArgumentList](../../xsltargumentlist/), der die namensraumqualifizierten Argumente enthält, die als Eingabe für die Transformation verwendet werden. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | Der TextWriter, in den Sie ausgeben möchten. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | Der [XmlResolver](../../../system.xml/xmlresolver/), der verwendet wird, um die XSLT **document()**-Funktion aufzulösen. Wenn dies **nullptr** ist, wird die **document()**-Funktion nicht aufgelöst. Der [XmlResolver](../../../system.xml/xmlresolver/) wird nach Abschluss dieser Methode nicht zwischengespeichert. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) Methode

Transformiert die XML-Daten im XPathNavigator mithilfe der angegebenen **args** und gibt das Ergebnis an einen TextWriter aus.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::TextWriter> &output)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Ein XPathNavigator, der die zu transformierenden Daten enthält. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Ein [XsltArgumentList](../../xsltargumentlist/), der die namensraumqualifizierten Argumente enthält, die als Eingabe für die Transformation verwendet werden. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | Der TextWriter, in den Sie ausgeben möchten. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) Methode

Transformiert die XML-Daten im IXPathNavigable mithilfe der angegebenen **args** und gibt das Ergebnis an ein [XmlReader](../../../system.xml/xmlreader/) aus.

```cpp
SharedPtr<XmlReader> System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Ein Objekt, das das IXPathNavigable-Interface implementiert. Es kann entweder ein [XmlNode](../../../system.xml/xmlnode/) (typischerweise ein [XmlDocument](../../../system.xml/xmldocument/)) oder ein XPathDocument sein, das die zu transformierenden Daten enthält. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Ein [XsltArgumentList](../../xsltargumentlist/), der die namensraumqualifizierten Argumente enthält, die als Eingabe für die Transformation verwendet werden. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | Der [XmlResolver](../../../system.xml/xmlresolver/), der verwendet wird, um die XSLT **document()**-Funktion aufzulösen. Wenn dies **nullptr** ist, wird die **document()**-Funktion nicht aufgelöst. Der [XmlResolver](../../../system.xml/xmlresolver/) wird nach Abschluss dieser Methode nicht zwischengespeichert. |

### Rückgabewert

Ein [XmlReader](../../../system.xml/xmlreader/) mit den Ergebnissen der Transformation.

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&) Methode

Transformiert die XML-Daten im IXPathNavigable mithilfe der angegebenen **args** und gibt das Ergebnis an ein [XmlReader](../../../system.xml/xmlreader/) aus.

```cpp
SharedPtr<XmlReader> System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Ein Objekt, das das IXPathNavigable-Interface implementiert. Es kann entweder ein [XmlNode](../../../system.xml/xmlnode/) (typischerweise ein [XmlDocument](../../../system.xml/xmldocument/)) oder ein XPathDocument sein, das die zu transformierenden Daten enthält. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Ein [XsltArgumentList](../../xsltargumentlist/), der die namensraumqualifizierten Argumente enthält, die als Eingabe für die Transformation verwendet werden. |

### Rückgabewert

Ein [XmlReader](../../../system.xml/xmlreader/) mit den Ergebnissen der Transformation.

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) Methode

Transformiert die XML-Daten im IXPathNavigable mithilfe der angegebenen **args** und gibt das Ergebnis an einen TextWriter aus.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::TextWriter> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Ein Objekt, das das IXPathNavigable-Interface implementiert. Es kann entweder ein [XmlNode](../../../system.xml/xmlnode/) (typischerweise ein [XmlDocument](../../../system.xml/xmldocument/)) oder ein XPathDocument sein, das die zu transformierenden Daten enthält. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Ein [XsltArgumentList](../../xsltargumentlist/), der die namensraumqualifizierten Argumente enthält, die als Eingabe für die Transformation verwendet werden. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | Der TextWriter, in den Sie ausgeben möchten. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | Der [XmlResolver](../../../system.xml/xmlresolver/), der verwendet wird, um die XSLT **document()**-Funktion aufzulösen. Wenn dies **nullptr** ist, wird die **document()**-Funktion nicht aufgelöst. Der [XmlResolver](../../../system.xml/xmlresolver/) wird nach Abschluss dieser Methode nicht zwischengespeichert. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) Methode

Transformiert die XML-Daten im IXPathNavigable mithilfe der angegebenen **args** und gibt das Ergebnis an einen TextWriter aus.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::TextWriter> &output)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Ein Objekt, das das IXPathNavigable-Interface implementiert. Es kann entweder ein [XmlNode](../../../system.xml/xmlnode/) (typischerweise ein [XmlDocument](../../../system.xml/xmldocument/)) oder ein XPathDocument sein, das die zu transformierenden Daten enthält. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Ein [XsltArgumentList](../../xsltargumentlist/), der die namensraumqualifizierten Argumente enthält, die als Eingabe für die Transformation verwendet werden. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | Der TextWriter, in den Sie ausgeben möchten. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) Methode

Transformiert die XML-Daten im IXPathNavigable mithilfe der angegebenen **args** und gibt das Ergebnis an einen Stream aus.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::Stream> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Ein Objekt, das das IXPathNavigable-Interface implementiert. Es kann entweder ein [XmlNode](../../../system.xml/xmlnode/) (typischerweise ein [XmlDocument](../../../system.xml/xmldocument/)) oder ein XPathDocument sein, das die zu transformierenden Daten enthält. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Ein [XsltArgumentList](../../xsltargumentlist/), der die namensraumqualifizierten Argumente enthält, die als Eingabe für die Transformation verwendet werden. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Der Stream, in den Sie ausgeben möchten. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | Der [XmlResolver](../../../system.xml/xmlresolver/), der verwendet wird, um die XSLT **document()**-Funktion aufzulösen. Wenn dies **nullptr** ist, wird die **document()**-Funktion nicht aufgelöst. Der [XmlResolver](../../../system.xml/xmlresolver/) wird nach Abschluss der [XslTransform::Transform](./)-Methode nicht zwischengespeichert. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) Methode

Transformiert die XML-Daten im IXPathNavigable mithilfe der angegebenen **args** und gibt das Ergebnis an einen Stream aus.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::Stream> &output)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Ein Objekt, das das IXPathNavigable-Interface implementiert. Es kann entweder ein [XmlNode](../../../system.xml/xmlnode/) (typischerweise ein [XmlDocument](../../../system.xml/xmldocument/)) oder ein XPathDocument sein, das die zu transformierenden Daten enthält. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Ein [XsltArgumentList](../../xsltargumentlist/), der die namensraumqualifizierten Argumente enthält, die als Eingabe für die Transformation verwendet werden. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Der Stream, in den Sie ausgeben möchten. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) Methode

Transformiert die XML-Daten im IXPathNavigable mithilfe der angegebenen **args** und gibt das Ergebnis an ein [XmlWriter](../../../system.xml/xmlwriter/) aus.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<XmlWriter> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Ein Objekt, das das IXPathNavigable-Interface implementiert. Es kann entweder ein [XmlNode](../../../system.xml/xmlnode/) (typischerweise ein [XmlDocument](../../../system.xml/xmldocument/)) oder ein XPathDocument sein, das die zu transformierenden Daten enthält. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Ein [XsltArgumentList](../../xsltargumentlist/), der die namensraumqualifizierten Argumente enthält, die als Eingabe für die Transformation verwendet werden. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | Der [XmlWriter](../../../system.xml/xmlwriter/), in den Sie ausgeben möchten. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | Der [XmlResolver](../../../system.xml/xmlresolver/), der verwendet wird, um die XSLT **document()**-Funktion aufzulösen. Wenn dies **nullptr** ist, wird die **document()**-Funktion nicht aufgelöst. Der [XmlResolver](../../../system.xml/xmlresolver/) wird nach Abschluss dieser Methode nicht zwischengespeichert. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) Methode

Transformiert die XML-Daten im IXPathNavigable mithilfe der angegebenen **args** und gibt das Ergebnis an ein [XmlWriter](../../../system.xml/xmlwriter/) aus.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<XmlWriter> &output)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Ein Objekt, das das IXPathNavigable-Interface implementiert. Es kann entweder ein [XmlNode](../../../system.xml/xmlnode/) (typischerweise ein [XmlDocument](../../../system.xml/xmldocument/)) oder ein XPathDocument sein, das die zu transformierenden Daten enthält. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Ein [XsltArgumentList](../../xsltargumentlist/), der die namensraumqualifizierten Argumente enthält, die als Eingabe für die Transformation verwendet werden. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | Der [XmlWriter](../../../system.xml/xmlwriter/), in den Sie ausgeben möchten. |

## XslTransform::Transform(const String\&, const String\&, const SharedPtr\<System::Xml::XmlResolver\>\&) Methode

Transformiert die XML-Daten in der Eingabedatei und gibt das Ergebnis in eine Ausgabedatei aus.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const String &inputfile, const String &outputfile, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputfile | const [String](../../../system/string/)\& | Die URL des zu transformierenden Quelldokuments. |
| outputfile | const [String](../../../system/string/)\& | Die URL der Ausgabedatei. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | Der [XmlResolver](../../../system.xml/xmlresolver/), der verwendet wird, um die XSLT **document()**-Funktion aufzulösen. Wenn dies **nullptr** ist, wird die **document()**-Funktion nicht aufgelöst. Der [XmlResolver](../../../system.xml/xmlresolver/) wird nach Abschluss der [XslTransform::Transform](./)-Methode nicht zwischengespeichert. |

## XslTransform::Transform(const String\&, const String\&) Methode

Transformiert die XML-Daten in der Eingabedatei und gibt das Ergebnis in eine Ausgabedatei aus.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const String &inputfile, const String &outputfile)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputfile | const [String](../../../system/string/)\& | Die URL des zu transformierenden Quelldokuments. |
| outputfile | const [String](../../../system/string/)\& | Die URL der Ausgabedatei. |

## Siehe auch

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