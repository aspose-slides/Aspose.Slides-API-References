---
title: XmlValidatingReader()
second_title: Aspose.Slides voor C++ API-referentie
description: Initialiseert een nieuw exemplaar van de XmlValidatingReader-klasse die de inhoud valideert die wordt geretourneerd door de opgegeven XmlReader.
type: docs
weight: 430
url: /nl/system.xml/xmlvalidatingreader/xmlvalidatingreader/
---
## XmlValidatingReader::XmlValidatingReader(const SharedPtr\<XmlReader\>\&) constructor

Initialiseert een nieuw exemplaar van de [XmlValidatingReader](../) klasse die de inhoud valideert die wordt geretourneerd door de opgegeven [XmlReader](../../xmlreader/).

```cpp
System::Xml::XmlValidatingReader::XmlValidatingReader(const SharedPtr<XmlReader> &reader)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\>\& | De [XmlReader](../../xmlreader/) om van te lezen tijdens het valideren. De huidige implementatie ondersteunt alleen [XmlTextReader](../../xmltextreader/). |

## XmlValidatingReader::XmlValidatingReader(const String\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) constructor

Initialiseert een nieuw exemplaar van de [XmlValidatingReader](../) klasse met de opgegeven waarden.

```cpp
System::Xml::XmlValidatingReader::XmlValidatingReader(const String &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| xmlFragment | const [String](../../../system/string/)\& | De tekenreeks die het XML-fragment bevat om te parseren. |
| fragType | [XmlNodeType](../../xmlnodetype/) | De XmlNodeType van het XML-fragment. Dit bepaalt ook wat de fragmenttekenreeks kan bevatten (zie tabel hieronder). |
| context | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | De [XmlParserContext](../../xmlparsercontext/) waarin het XML-fragment moet worden geparseerd. Dit omvat de [NameTable](../../nametable/) die moet worden gebruikt, codering, namespace-bereik, huidige **xml:lang**, en **xml:space** bereik. |

## Opmerkingen

De volgende tabel geeft geldige waarden voor **fragType** weer en hoe de lezer elk van de verschillende knoop-typen verwerkt.

| XmlNodeType | Fragment mag bevatten |
| --- | --- |
| Element| Elke geldige elementinhoud (bijvoorbeeld een combinatie van elementen, commentaren, verwerkingsinstructies, cdata, tekst en entiteitsreferenties). |
| [Attribute](../../../system/attribute/)| De waarde van een attribuut (het gedeelte tussen de aanhalingstekens). |
| Document| De inhoud van een compleet XML-document; dit handhaaft regels op documentniveau. |

## XmlValidatingReader::XmlValidatingReader(const SharedPtr\<IO::Stream\>\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) constructor

Initialiseert een nieuw exemplaar van de [XmlValidatingReader](../) klasse met de opgegeven waarden.

```cpp
System::Xml::XmlValidatingReader::XmlValidatingReader(const SharedPtr<IO::Stream> &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| xmlFragment | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | De stream die het XML-fragment bevat om te parseren. |
| fragType | [XmlNodeType](../../xmlnodetype/) | De XmlNodeType van het XML-fragment. Dit bepaalt wat het fragment kan bevatten (zie tabel hieronder). |
| context | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | De [XmlParserContext](../../xmlparsercontext/) waarin het XML-fragment moet worden geparseerd. Dit omvat de [XmlNameTable](../../xmlnametable/) die moet worden gebruikt, codering, namespace-bereik, huidige **xml:lang**, en **xml:space** bereik. |

## Opmerkingen

De volgende tabel geeft geldige waarden voor **fragType** weer en hoe de lezer elk van de verschillende knoop-typen verwerkt.

| XmlNodeType | Fragment mag bevatten |
| --- | --- |
| Element| Elke geldige elementinhoud (bijvoorbeeld een combinatie van elementen, commentaren, verwerkingsinstructies, cdata, tekst en entiteitsreferenties). |
| [Attribute](../../../system/attribute/)| De waarde van een attribuut (het gedeelte tussen de aanhalingstekens). |
| Document| De inhoud van een compleet XML-document; dit handhaaft regels op documentniveau. |

## Zie ook

* Enum [XmlNodeType](../../xmlnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../xmlreader/)
* Class [XmlValidatingReader](../)
* Class [String](../../../system/string/)
* Class [XmlParserContext](../../xmlparsercontext/)
* Class [Stream](../../../system.io/stream/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)