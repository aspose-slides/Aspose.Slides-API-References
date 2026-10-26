---
title: XmlTextReader()
second_title: Aspose.Slides voor C++ API-referentie
description: Initialiseert een nieuw exemplaar van de XmlTextReader-klasse met de opgegeven stream.
type: docs
weight: 482
url: /nl/system.xml/xmltextreader/xmltextreader/
---
## XmlTextReader::XmlTextReader(const SharedPtr\<IO::Stream\>\&) constructor

Initialiseert een nieuw exemplaar van de [XmlTextReader](../) klasse met de opgegeven stream.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::Stream> &input)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | De stream die de XML-gegevens bevat die gelezen moet worden. |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::Stream\>\&) constructor

Initialiseert een nieuw exemplaar van de [XmlTextReader](../) klasse met de opgegeven URL en stream.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::Stream> &input)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | De URL die gebruikt wordt voor het oplossen van externe bronnen. De [XmlTextReader::get_BaseURI](../get_baseuri/) wordt op deze waarde ingesteld. |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | De stream die de XML-gegevens bevat die gelezen moet worden. |

## XmlTextReader::XmlTextReader(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlNameTable\>\&) constructor

Initialiseert een nieuw exemplaar van de [XmlTextReader](../) klasse met de opgegeven stream en [XmlNameTable](../../xmlnametable/).

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::Stream> &input, const SharedPtr<XmlNameTable> &nt)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | De stream die de XML-gegevens bevat die gelezen moet worden. |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | De [XmlNameTable](../../xmlnametable/) die gebruikt wordt. |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlNameTable\>\&) constructor

Initialiseert een nieuw exemplaar van de [XmlTextReader](../) klasse met de opgegeven URL, stream en [XmlNameTable](../../xmlnametable/).

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::Stream> &input, const SharedPtr<XmlNameTable> &nt)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | De URL die gebruikt wordt voor het oplossen van externe bronnen. De [XmlTextReader::get_BaseURI](../get_baseuri/) wordt op deze waarde ingesteld. Als **url** **nullptr** is, wordt **BaseURI** ingesteld op [String::Empty](../../../system/string/empty/). |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | De stream die de XML-gegevens bevat die gelezen moet worden. |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | De [XmlNameTable](../../xmlnametable/) die gebruikt wordt. |

## XmlTextReader::XmlTextReader(const SharedPtr\<IO::TextReader\>\&) constructor

Initialiseert een nieuw exemplaar van de [XmlTextReader](../) klasse met de opgegeven TextReader.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::TextReader> &input)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | De TextReader die de XML-gegevens bevat die gelezen moet worden. |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::TextReader\>\&) constructor

Initialiseert een nieuw exemplaar van de [XmlTextReader](../) klasse met de opgegeven URL en TextReader.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::TextReader> &input)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | De URL die gebruikt wordt voor het oplossen van externe bronnen. De [XmlTextReader::get_BaseURI](../get_baseuri/) wordt op deze waarde ingesteld. |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | De TextReader die de XML-gegevens bevat die gelezen moet worden. |

## XmlTextReader::XmlTextReader(const SharedPtr\<IO::TextReader\>\&, const SharedPtr\<XmlNameTable\>\&) constructor

Initialiseert een nieuw exemplaar van de [XmlTextReader](../) klasse met de opgegeven TextReader en [XmlNameTable](../../xmlnametable/).

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::TextReader> &input, const SharedPtr<XmlNameTable> &nt)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | De TextReader die de XML-gegevens bevat die gelezen moet worden. |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | De [XmlNameTable](../../xmlnametable/) die gebruikt wordt. |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::TextReader\>\&, const SharedPtr\<XmlNameTable\>\&) constructor

Initialiseert een nieuw exemplaar van de [XmlTextReader](../) klasse met de opgegeven URL, TextReader en [XmlNameTable](../../xmlnametable/).

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::TextReader> &input, const SharedPtr<XmlNameTable> &nt)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | De URL die gebruikt wordt voor het oplossen van externe bronnen. De [XmlTextReader::get_BaseURI](../get_baseuri/) wordt op deze waarde ingesteld. Als **url** **nullptr** is, wordt **BaseURI** ingesteld op [String::Empty](../../../system/string/empty/). |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | De TextReader die de XML-gegevens bevat die gelezen moet worden. |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | De [XmlNameTable](../../xmlnametable/) die gebruikt wordt. |

## XmlTextReader::XmlTextReader(const SharedPtr\<IO::Stream\>\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) constructor

Initialiseert een nieuw exemplaar van de [XmlTextReader](../) klasse met de opgegeven stream, XmlNodeType en [XmlParserContext](../../xmlparsercontext/).

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::Stream> &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| xmlFragment | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | De stream die het XML-fragment bevat dat geparseerd moet worden. |
| fragType | [XmlNodeType](../../xmlnodetype/) | Het XmlNodeType van het XML-fragment. Dit bepaalt ook wat het fragment kan bevatten. |
| context | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | De [XmlParserContext](../../xmlparsercontext/) waarin de **xmlFragment** geparseerd wordt. Dit omvat de [XmlNameTable](../../xmlnametable/) die gebruikt wordt, codering, namespace-scope, de huidige **xml:lang**, en de **xml:space**-scope. |

## XmlTextReader::XmlTextReader(const String\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) constructor

Initialiseert een nieuw exemplaar van de [XmlTextReader](../) klasse met de opgegeven string, XmlNodeType en [XmlParserContext](../../xmlparsercontext/).

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| xmlFragment | const [String](../../../system/string/)\& | De string die het XML-fragment bevat dat geparseerd moet worden. |
| fragType | [XmlNodeType](../../xmlnodetype/) | Het XmlNodeType van het XML-fragment. Dit bepaalt ook wat de fragment-string kan bevatten. |
| context | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | De [XmlParserContext](../../xmlparsercontext/) waarin de **xmlFragment** geparseerd wordt. Dit omvat de [XmlNameTable](../../xmlnametable/) die gebruikt wordt, codering, namespace-scope, de huidige **xml:lang**, en de **xml:space**-scope. |

## XmlTextReader::XmlTextReader(const String\&) constructor

Initialiseert een nieuw exemplaar van de [XmlTextReader](../) klasse met het opgegeven bestand.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | De URL van het bestand dat de XML-gegevens bevat. De [XmlTextReader::get_BaseURI](../get_baseuri/) wordt op deze waarde ingesteld. |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<XmlNameTable\>\&) constructor

Initialiseert een nieuw exemplaar van de [XmlTextReader](../) klasse met het opgegeven bestand en [XmlNameTable](../../xmlnametable/).

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<XmlNameTable> &nt)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | De URL van het bestand dat de XML-gegevens bevat die gelezen moet worden. |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | De [XmlNameTable](../../xmlnametable/) die gebruikt wordt. |

## Zie ook

* Enum [XmlNodeType](../../xmlnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Stream](../../../system.io/stream/)
* Klasse [XmlTextReader](../)
* Klasse [String](../../../system/string/)
* Klasse [XmlNameTable](../../xmlnametable/)
* Klasse [TextReader](../../../system.io/textreader/)
* Klasse [XmlParserContext](../../xmlparsercontext/)
* Namespace [System::Xml](../../)
* Bibliotheek [Aspose.Slides](../../../)