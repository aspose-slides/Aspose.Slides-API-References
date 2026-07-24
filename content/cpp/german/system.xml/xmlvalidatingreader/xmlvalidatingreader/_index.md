---
title: XmlValidatingReader()
second_title: Aspose.Slides für C++ API Referenz
description: Initialisiert eine neue Instanz der XmlValidatingReader-Klasse, die den von dem angegebenen XmlReader zurückgegebenen Inhalt validiert.
type: docs
weight: 430
url: /de/system.xml/xmlvalidatingreader/xmlvalidatingreader/
---
## XmlValidatingReader::XmlValidatingReader(const SharedPtr\<XmlReader\>\&) Konstruktor


Initialisiert eine neue Instanz der [XmlValidatingReader](../) Klasse, die den von dem angegebenen [XmlReader](../../xmlreader/) zurückgegebenen Inhalt validiert.

```cpp
System::Xml::XmlValidatingReader::XmlValidatingReader(const SharedPtr<XmlReader> &reader)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\>\& | Der [XmlReader](../../xmlreader/) zum Lesen während der Validierung. Die aktuelle Implementierung unterstützt nur [XmlTextReader](../../xmltextreader/). |

## XmlValidatingReader::XmlValidatingReader(const String\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) Konstruktor


Initialisiert eine neue Instanz der [XmlValidatingReader](../) Klasse mit den angegebenen Werten.

```cpp
System::Xml::XmlValidatingReader::XmlValidatingReader(const String &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| xmlFragment | const [String](../../../system/string/)\& | Die Zeichenkette, die das zu parsende XML-Fragment enthält. |
| fragType | [XmlNodeType](../../xmlnodetype/) | Der XmlNodeType des XML-Fragments. Dieser bestimmt auch, was die Fragmentzeichenkette enthalten kann (siehe Tabelle unten). |
| context | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | Der [XmlParserContext](../../xmlparsercontext/) in dem das XML-Fragment geparst werden soll. Dieser umfasst das zu verwendende [NameTable](../../nametable/), die Kodierung, den Namensbereich, den aktuellen **xml:lang**- und **xml:space**-Bereich. |

## Anmerkungen



Die folgende Tabelle listet gültige Werte für **fragType** und wie der Reader die verschiedenen Knotentypen verarbeitet. 

| XmlNodeType | Fragment kann enthalten |
| --- | --- |
| Element| Jeder gültige Elementinhalt (zum Beispiel jede Kombination aus Elementen, Kommentaren, Verarbeitungsanweisungen, CDATA, Text und Entity-Referenzen). |
| [Attribute](../../../system/attribute/)| Der Wert eines Attributs (der Teil innerhalb der Anführungszeichen). |
| Document| Der Inhalt eines gesamten XML-Dokuments; dies erzwingt Dokument-Ebene-Regeln. |


## XmlValidatingReader::XmlValidatingReader(const SharedPtr\<IO::Stream\>\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) Konstruktor


Initialisiert eine neue Instanz der [XmlValidatingReader](../) Klasse mit den angegebenen Werten.

```cpp
System::Xml::XmlValidatingReader::XmlValidatingReader(const SharedPtr<IO::Stream> &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| xmlFragment | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Der Stream, der das zu parsende XML-Fragment enthält. |
| fragType | [XmlNodeType](../../xmlnodetype/) | Der XmlNodeType des XML-Fragments. Dieser bestimmt, was das Fragment enthalten kann (siehe Tabelle unten). |
| context | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | Der [XmlParserContext](../../xmlparsercontext/) in dem das XML-Fragment geparst werden soll. Dieser umfasst das zu verwendende [XmlNameTable](../../xmlnametable/), die Kodierung, den Namensbereich, den aktuellen **xml:lang**- und **xml:space**-Bereich. |

## Anmerkungen



Die folgende Tabelle listet gültige Werte für **fragType** und wie der Reader die verschiedenen Knotentypen verarbeitet. 

| XmlNodeType | Fragment kann enthalten |
| --- | --- |
| Element| Jeder gültige Elementinhalt (zum Beispiel jede Kombination aus Elementen, Kommentaren, Verarbeitungsanweisungen, CDATA, Text und Entity-Referenzen). |
| [Attribute](../../../system/attribute/)| Der Wert eines Attributs (der Teil innerhalb der Anführungszeichen). |
| Document| Der Inhalt eines gesamten XML-Dokuments; dies erzwingt Dokument-Ebene-Regeln. |


## Siehe auch

* Enum [XmlNodeType](../../xmlnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlReader](../../xmlreader/)
* Klasse [XmlValidatingReader](../)
* Klasse [String](../../../system/string/)
* Klasse [XmlParserContext](../../xmlparsercontext/)
* Klasse [Stream](../../../system.io/stream/)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)