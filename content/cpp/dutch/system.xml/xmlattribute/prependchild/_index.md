---
title: PrependChild()
second_title: Aspose.Slides voor C++ API-referentie
description: Voegt het opgegeven knooppunt toe aan het begin van de lijst met onderliggende knooppunten voor dit knooppunt.
type: docs
weight: 261
url: /nl/system.xml/xmlattribute/prependchild/
---
## XmlAttribute::PrependChild(SharedPtr\<XmlNode\>) methode

Voegt het opgegeven knooppunt toe aan het begin van de lijst met onderliggende knooppunten voor dit knooppunt.

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttribute::PrependChild(SharedPtr<XmlNode> newChild) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | De [XmlNode](../../xmlnode/) die moet worden toegevoegd. Als het een [XmlDocumentFragment](../../xmldocumentfragment/) is, wordt de volledige inhoud van het documentfragment verplaatst naar de lijst met onderliggende knooppunten van dit knooppunt. |

### Retourwaarde

De [XmlNode](../../xmlnode/) toegevoegd.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlNode](../../xmlnode/)
* Klasse [XmlAttribute](../)
* Naamruimte [System::Xml](../../)
* Bibliotheek [Aspose.Slides](../../../)