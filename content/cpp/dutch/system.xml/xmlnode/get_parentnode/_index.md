---
title: get_ParentNode()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert de ouder van dit knooppunt (voor knooppunten die ouders kunnen hebben).
type: docs
weight: 53
url: /nl/system.xml/xmlnode/get_parentnode/
---
## XmlNode::get_ParentNode() methode


Retourneert de ouder van dit knooppunt (voor knooppunten die ouders kunnen hebben).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNode::get_ParentNode() final
```


### Retourwaarde

De [XmlNode](../) die de ouder is van het huidige knooppunt.
## Opmerkingen



Als een knooppunt zojuist is gemaakt en nog niet aan de boom is toegevoegd, of als het uit de boom is verwijderd, is de ouder **nullptr**. Voor alle andere knooppunten hangt de geretourneerde waarde af van de [XmlNode::get_NodeType](../get_nodetype/) van het knooppunt. De volgende tabel beschrijft de mogelijke retourwaarden voor de **get_NodeType**-methode. 

| NodeType | Retourwaarde van ParentNode |
| --- | --- |
| [Attribute](../../../system/attribute/), Document, DocumentFragment, Entity, Notation | Retourneert `nullptr`; deze knooppunten hebben geen ouders. |
| CDATA | Retourneert het element of de entiteitsreferentie die de CDATA-sectie bevat. |
| Comment | Retourneert het element, de entiteitsreferentie, het documenttype of het document dat de Comment bevat. |
| DocumentType | Retourneert het documentknooppunt. |
| Element | Retourneert het ouderknooppunt van het element. Als het element het wortelknooppunt in de boom is, is de ouder het documentknooppunt. |
| EntityReference | Retourneert het element, het attribuut of de entiteitsreferentie die de EntityReference bevat. |
| ProcessingInstruction | Retourneert het document, het element, het documenttype of de entiteitsreferentie die de ProcessingInstruction bevat. |
| [Text](../../../system.text/)| Retourneert het ouder-element, het attribuut of de entiteitsreferentie die het tekstknooppunt bevat. |


## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)