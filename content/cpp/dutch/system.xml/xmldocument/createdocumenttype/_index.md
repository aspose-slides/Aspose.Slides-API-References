---
title: CreateDocumentType()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert een nieuw XmlDocumentType-object.
type: docs
weight: 313
url: /nl/system.xml/xmldocument/createdocumenttype/
---
## XmlDocument::CreateDocumentType(const String\&, const String\&, const String\&, const String\&) method

Retourneert een nieuw [XmlDocumentType](../../xmldocumenttype/) object.

```cpp
virtual SharedPtr<XmlDocumentType> System::Xml::XmlDocument::CreateDocumentType(const String &name, const String &publicId, const String &systemId, const String &internalSubset)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Naam van het documenttype. |
| publicId | const [String](../../../system/string/)\& | De publieke identifier van het documenttype of **nullptr**. Je kunt een publieke URI en ook een systeemidentifier opgeven om de locatie van de externe DTD-subset te identificeren. |
| systemId | const [String](../../../system/string/)\& | De systeemidentifier van het documenttype of **nullptr**. Specificeert de URL van de bestandslocatie voor de externe DTD-subset. |
| internalSubset | const [String](../../../system/string/)\& | De interne DTD-subset van het documenttype of **nullptr**. |

### Retourwaarde

Het nieuwe [XmlDocumentType](../../xmldocumenttype/).

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlDocumentType](../../xmldocumenttype/)
* Klasse [String](../../../system/string/)
* Klasse [XmlDocument](../)
* Naamruimte [System::Xml](../../)
* Bibliotheek [Aspose.Slides](../../../)