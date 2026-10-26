---
title: Save()
second_title: Aspose.Slides voor C++ API Referentie
description: Slaat het XML-document op in het opgegeven bestand. Als het opgegeven bestand bestaat, overschrijft deze methode het.
type: docs
weight: 534
url: /nl/system.xml/xmldocument/save/
---
## XmlDocument::Save(String) methode


Slaat het XML-document op in het opgegeven bestand. Als het opgegeven bestand bestaat, overschrijft deze methode het.

```cpp
virtual void System::Xml::XmlDocument::Save(String filename)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filename | [String](../../../system/string/) | De locatie van het bestand waarin u het document wilt opslaan. |

## XmlDocument::Save(SharedPtr\<IO::Stream\>) methode


Slaat het XML-document op in de opgegeven stream.

```cpp
virtual void System::Xml::XmlDocument::Save(SharedPtr<IO::Stream> outStream)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| outStream | [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | De stroom waarin u wilt opslaan. |

## XmlDocument::Save(SharedPtr\<IO::TextWriter\>) methode


Slaat het XML-document op in de opgegeven TextWriter.

```cpp
virtual void System::Xml::XmlDocument::Save(SharedPtr<IO::TextWriter> writer)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| writer | [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\> | De TextWriter waarin u wilt opslaan. |

## XmlDocument::Save(SharedPtr\<XmlWriter\>) methode


Slaat het XML-document op in de opgegeven [XmlWriter](../../xmlwriter/).

```cpp
virtual void System::Xml::XmlDocument::Save(SharedPtr<XmlWriter> w)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| w | [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../xmlwriter/)\> | De [XmlWriter](../../xmlwriter/) waarin u wilt opslaan. |

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [String](../../../system/string/)
* Klasse [XmlDocument](../)
* Klasse [Stream](../../../system.io/stream/)
* Klasse [TextWriter](../../../system.io/textwriter/)
* Klasse [XmlWriter](../../xmlwriter/)
* Naamruimte [System::Xml](../../)
* Bibliotheek [Aspose.Slides](../../../)