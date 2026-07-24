---
title: Transform()
second_title: Aspose.Slides für C++ API-Referenz
description: Führt die Transformation mit dem durch das IXPathNavigable-Objekt angegebenen Eingabedokument aus und gibt die Ergebnisse an einen XmlWriter aus.
type: docs
weight: 40
url: /de/system.xml.xsl/xslcompiledtransform/transform/
---
## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XmlWriter\>\&) method

Führt die Transformation aus, indem das durch das IXPathNavigable-Objekt angegebene Eingabedokument verwendet wird, und gibt die Ergebnisse an ein [XmlWriter](../../../system.xml/xmlwriter/) aus.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XmlWriter> &results)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Ein Objekt, das die IXPathNavigable Schnittstelle implementiert. Es kann entweder ein [XmlNode](../../../system.xml/xmlnode/) (typischerweise ein [XmlDocument](../../../system.xml/xmldocument/)) oder ein XPathDocument sein, das die zu transformierenden Daten enthält. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | Das [XmlWriter](../../../system.xml/xmlwriter/), in das Sie ausgeben möchten. Wenn das Stylesheet ein **xsl:output**-Element enthält, sollten Sie das [XmlWriter](../../../system.xml/xmlwriter/) mit dem [XmlWriterSettings](../../../system.xml/xmlwritersettings/)-Objekt erstellen, das aus dem [XslCompiledTransform::get_OutputSettings](../get_outputsettings/)-Wert zurückgegeben wird. Dies stellt sicher, dass [XmlWriter](../../../system.xml/xmlwriter/) die korrekten Ausgabeeinstellungen hat. |

## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) method

Führt die Transformation aus, wobei das durch das IXPathNavigable-Objekt angegebene Eingabedokument verwendet wird, und gibt die Ergebnisse an ein [XmlWriter](../../../system.xml/xmlwriter/) aus. Der [XsltArgumentList](../../xsltargumentlist/) stellt zusätzliche Laufzeitargumente bereit.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Ein Objekt, das die IXPathNavigable Schnittstelle implementiert. Es kann entweder ein [XmlNode](../../../system.xml/xmlnode/) (typischerweise ein [XmlDocument](../../../system.xml/xmldocument/)) oder ein XPathDocument sein, das die zu transformierenden Daten enthält. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Ein [XsltArgumentList](../../xsltargumentlist/), das die namensqualifizierten Argumente enthält, die als Eingabe für die Transformation verwendet werden. Dieser Wert kann **nullptr** sein. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | Das [XmlWriter](../../../system.xml/xmlwriter/), in das Sie ausgeben möchten. Wenn das Stylesheet ein **xsl:output**-Element enthält, sollten Sie das [XmlWriter](../../../system.xml/xmlwriter/) mit dem [XmlWriterSettings](../../../system.xml/xmlwritersettings/)-Objekt erstellen, das aus dem [XslCompiledTransform::get_OutputSettings](../get_outputsettings/)-Wert zurückgegeben wird. Dies stellt sicher, dass [XmlWriter](../../../system.xml/xmlwriter/) die korrekten Ausgabeeinstellungen hat. |

## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) method

Führt die Transformation aus, wobei das durch das IXPathNavigable-Objekt angegebene Eingabedokument verwendet wird, und gibt die Ergebnisse an einen TextWriter aus. Der [XsltArgumentList](../../xsltargumentlist/) stellt zusätzliche Laufzeitargumente bereit.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::TextWriter> &results)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Ein Objekt, das die IXPathNavigable Schnittstelle implementiert. Es kann entweder ein [XmlNode](../../../system.xml/xmlnode/) (typischerweise ein [XmlDocument](../../../system.xml/xmldocument/)) oder ein XPathDocument sein, das die zu transformierenden Daten enthält. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Ein [XsltArgumentList](../../xsltargumentlist/), das die namensqualifizierten Argumente enthält, die als Eingabe für die Transformation verwendet werden. Dieser Wert kann **nullptr** sein. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | Der TextWriter, in den Sie ausgeben möchten. |

## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) method

Führt die Transformation aus, wobei das durch das IXPathNavigable-Objekt angegebene Eingabedokument verwendet wird, und gibt die Ergebnisse in einen Stream aus. Der [XsltArgumentList](../../xsltargumentlist/) stellt zusätzliche Laufzeitargumente bereit.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::Stream> &results)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Ein Objekt, das die IXPathNavigable Schnittstelle implementiert. Es kann entweder ein [XmlNode](../../../system.xml/xmlnode/) (typischerweise ein [XmlDocument](../../../system.xml/xmldocument/)) oder ein XPathDocument sein, das die zu transformierenden Daten enthält. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Ein [XsltArgumentList](../../xsltargumentlist/), das die namensqualifizierten Argumente enthält, die als Eingabe für die Transformation verwendet werden. Dieser Wert kann **nullptr** sein. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Der Stream, in den Sie ausgeben möchten. |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XmlWriter\>\&) method

Führt die Transformation aus, wobei das durch das [XmlReader](../../../system.xml/xmlreader/)-Objekt angegebene Eingabedokument verwendet wird, und gibt die Ergebnisse an ein [XmlWriter](../../../system.xml/xmlwriter/) aus.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XmlWriter> &results)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Der [XmlReader](../../../system.xml/xmlreader/) enthält das Eingabedokument. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | Der [XmlWriter](../../../system.xml/xmlwriter/), in den Sie ausgeben möchten. Wenn das Stylesheet ein **xsl:output**-Element enthält, sollten Sie das [XmlWriter](../../../system.xml/xmlwriter/) mit dem [XmlWriterSettings](../../../system.xml/xmlwritersettings/)-Objekt erstellen, das aus dem [XslCompiledTransform::get_OutputSettings](../get_outputsettings/)-Wert zurückgegeben wird. Dies stellt sicher, dass [XmlWriter](../../../system.xml/xmlwriter/) die korrekten Ausgabeeinstellungen hat. |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) method

Führt die Transformation aus, wobei das durch das [XmlReader](../../../system.xml/xmlreader/)-Objekt angegebene Eingabedokument verwendet wird, und gibt die Ergebnisse an ein [XmlWriter](../../../system.xml/xmlwriter/) aus. Der [XsltArgumentList](../../xsltargumentlist/) stellt zusätzliche Laufzeitargumente bereit.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Ein [XmlReader](../../../system.xml/xmlreader/) enthält das Eingabedokument. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Ein [XsltArgumentList](../../xsltargumentlist/), das die namensqualifizierten Argumente enthält, die als Eingabe für die Transformation verwendet werden. Dieser Wert kann **nullptr** sein. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | Der [XmlWriter](../../../system.xml/xmlwriter/), in den Sie ausgeben möchten. Wenn das Stylesheet ein **xsl:output**-Element enthält, sollten Sie das [XmlWriter](../../../system.xml/xmlwriter/) mit dem [XmlWriterSettings](../../../system.xml/xmlwritersettings/)-Objekt erstellen, das aus dem [XslCompiledTransform::get_OutputSettings](../get_outputsettings/)-Wert zurückgegeben wird. Dies stellt sicher, dass [XmlWriter](../../../system.xml/xmlwriter/) die korrekten Ausgabeeinstellungen hat. |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) method

Führt die Transformation aus, wobei das durch das [XmlReader](../../../system.xml/xmlreader/)-Objekt angegebene Eingabedokument verwendet wird, und gibt die Ergebnisse an einen TextWriter aus. Der [XsltArgumentList](../../xsltargumentlist/) stellt zusätzliche Laufzeitargumente bereit.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::TextWriter> &results)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Ein [XmlReader](../../../system.xml/xmlreader/) enthält das Eingabedokument. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Ein [XsltArgumentList](../../xsltargumentlist/), das die namensqualifizierten Argumente enthält, die als Eingabe für die Transformation verwendet werden. Dieser Wert kann **nullptr** sein. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | Der TextWriter, in den Sie ausgeben möchten. |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) method

Führt die Transformation aus, wobei das durch das [XmlReader](../../../system.xml/xmlreader/)-Objekt angegebene Eingabedokument verwendet wird, und gibt die Ergebnisse in einen Stream aus. Der [XsltArgumentList](../../xsltargumentlist/) stellt zusätzliche Laufzeitargumente bereit.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::Stream> &results)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Ein [XmlReader](../../../system.xml/xmlreader/) enthält das Eingabedokument. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Ein [XsltArgumentList](../../xsltargumentlist/), das die namensqualifizierten Argumente enthält, die als Eingabe für die Transformation verwendet werden. Dieser Wert kann **nullptr** sein. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Der Stream, in den Sie ausgeben möchten. |

## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XmlWriter\>\&) method

Führt die Transformation aus, wobei das durch die URI angegebene Eingabedokument verwendet wird, und gibt die Ergebnisse an ein [XmlWriter](../../../system.xml/xmlwriter/) aus.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XmlWriter> &results)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | Die URI des Eingabedokuments. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | Der [XmlWriter](../../../system.xml/xmlwriter/), in den Sie ausgeben möchten. Wenn das Stylesheet ein **xsl:output**-Element enthält, sollten Sie das [XmlWriter](../../../system.xml/xmlwriter/) mit dem [XmlWriterSettings](../../../system.xml/xmlwritersettings/)-Objekt erstellen, das aus dem [XslCompiledTransform::get_OutputSettings](../get_outputsettings/)-Wert zurückgegeben wird. Dies stellt sicher, dass [XmlWriter](../../../system.xml/xmlwriter/) die korrekten Ausgabeeinstellungen hat. |

## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) method

Führt die Transformation aus, wobei das durch die URI angegebene Eingabedokument verwendet wird, und gibt die Ergebnisse an ein [XmlWriter](../../../system.xml/xmlwriter/) aus. Der [XsltArgumentList](../../xsltargumentlist/) stellt zusätzliche Laufzeitargumente bereit.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | Die URI des Eingabedokuments. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Ein [XsltArgumentList](../../xsltargumentlist/), das die namensqualifizierten Argumente enthält, die als Eingabe für die Transformation verwendet werden. Dieser Wert kann **nullptr** sein. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | Der [XmlWriter](../../../system.xml/xmlwriter/), in den Sie ausgeben möchten. Wenn das Stylesheet ein **xsl:output**-Element enthält, sollten Sie das [XmlWriter](../../../system.xml/xmlwriter/) mit dem [XmlWriterSettings](../../../system.xml/xmlwritersettings/)-Objekt erstellen, das aus dem [XslCompiledTransform::get_OutputSettings](../get_outputsettings/)-Wert zurückgegeben wird. Dies stellt sicher, dass [XmlWriter](../../../system.xml/xmlwriter/) die korrekten Ausgabeeinstellungen hat. |

## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) method

Führt die Transformation aus, wobei das durch die URI angegebene Eingabedokument verwendet wird, und gibt die Ergebnisse an einen TextWriter aus.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::TextWriter> &results)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | Die URI des Eingabedokuments. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Ein [XsltArgumentList](../../xsltargumentlist/), das die namensqualifizierten Argumente enthält, die als Eingabe für die Transformation verwendet werden. Dieser Wert kann **nullptr** sein. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | Der TextWriter, in den Sie ausgeben möchten. |

## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) method

Führt die Transformation aus, wobei das durch die URI angegebene Eingabedokument verwendet wird, und gibt die Ergebnisse in einen Stream aus. Der [XsltArgumentList](../../xsltargumentlist/) stellt zusätzliche Laufzeitargumente bereit.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::Stream> &results)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | Die URI des Eingabedokuments. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Ein [XsltArgumentList](../../xsltargumentlist/), das die namensqualifizierten Argumente enthält, die als Eingabe für die Transformation verwendet werden. Dieser Wert kann **nullptr** sein. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Der Stream, in den Sie ausgeben möchten. |

## XslCompiledTransform::Transform(const String\&, const String\&) method

Führt die Transformation aus, wobei das durch die URI angegebene Eingabedokument verwendet wird, und gibt die Ergebnisse in eine Datei aus.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const String &resultsFile)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | Die URI des Eingabedokuments. |
| resultsFile | const [String](../../../system/string/)\& | Die URI der Ausgabedatei. |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<XmlResolver\>\&) method

Führt die Transformation aus, wobei das durch das [XmlReader](../../../system.xml/xmlreader/)-Objekt angegebene Eingabedokument verwendet wird, und gibt die Ergebnisse an ein [XmlWriter](../../../system.xml/xmlwriter/) aus. Der [XsltArgumentList](../../xsltargumentlist/) stellt zusätzliche Laufzeitargumente bereit und der [XmlResolver](../../../system.xml/xmlresolver/) löst die XSLT **document()**-Funktion auf.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results, const SharedPtr<XmlResolver> &documentResolver)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Ein [XmlReader](../../../system.xml/xmlreader/) enthält das Eingabedokument. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Ein [XsltArgumentList](../../xsltargumentlist/) enthält die namensqualifizierten Argumente, die als Eingabe für die Transformation verwendet werden. Dieser Wert kann **nullptr** sein. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | Der [XmlWriter](../../../system.xml/xmlwriter/), in den Sie ausgeben möchten. Wenn das Stylesheet ein **xsl:output**-Element enthält, sollten Sie das [XmlWriter](../../../system.xml/xmlwriter/) mit dem [XmlWriterSettings](../../../system.xml/xmlwritersettings/)-Objekt erstellen, das aus dem [XslCompiledTransform::get_OutputSettings](../get_outputsettings/)-Wert zurückgegeben wird. Dies stellt sicher, dass [XmlWriter](../../../system.xml/xmlwriter/) die korrekten Ausgabeeinstellungen hat. |
| documentResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | Der [XmlResolver](../../../system.xml/xmlresolver/) wird verwendet, um die XSLT **document()**-Funktion aufzulösen. Wenn dieser **nullptr** ist, wird die **document()**-Funktion nicht aufgelöst. |

## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<XmlResolver\>\&) method

Führt die Transformation aus, wobei das durch das IXPathNavigable-Objekt angegebene Eingabedokument verwendet wird, und gibt die Ergebnisse an ein [XmlWriter](../../../system.xml/xmlwriter/) aus. Der [XsltArgumentList](../../xsltargumentlist/) stellt zusätzliche Laufzeitargumente bereit und der [XmlResolver](../../../system.xml/xmlresolver/) löst die XSLT **document()**-Funktion auf.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results, const SharedPtr<XmlResolver> &documentResolver)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Das Dokument, das transformiert werden soll und durch das IXPathNavigable-Objekt angegeben ist. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Argumentliste als [XsltArgumentList](../../xsltargumentlist/). |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | Der [XmlWriter](../../../system.xml/xmlwriter/), in den Sie ausgeben möchten. Wenn das Stylesheet ein **xsl:output**-Element enthält, sollten Sie das [XmlWriter](../../../system.xml/xmlwriter/) mit dem [XmlWriterSettings](../../../system.xml/xmlwritersettings/)-Objekt erstellen, das aus dem [XslCompiledTransform::get_OutputSettings](../get_outputsettings/)-Wert zurückgegeben wird. Dies stellt sicher, dass [XmlWriter](../../../system.xml/xmlwriter/) die korrekten Ausgabeeinstellungen hat. |
| documentResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | Der [XmlResolver](../../../system.xml/xmlresolver/) wird verwendet, um die XSLT **document()**-Funktion aufzulösen. Wenn dieser **nullptr** ist, wird die **document()**-Funktion nicht aufgelöst. |

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Klasse [XmlWriter](../../../system.xml/xmlwriter/)
* Klasse [XslCompiledTransform](../)
* Klasse [XsltArgumentList](../../xsltargumentlist/)
* Klasse [TextWriter](../../../system.io/textwriter/)
* Klasse [Stream](../../../system.io/stream/)
* Klasse [XmlReader](../../../system.xml/xmlreader/)
* Klasse [String](../../../system/string/)
* Klasse [XmlResolver](../../../system.xml/xmlresolver/)
* Namensraum [System::Xml::Xsl](../../)
* Bibliothek [Aspose.Slides](../../../)