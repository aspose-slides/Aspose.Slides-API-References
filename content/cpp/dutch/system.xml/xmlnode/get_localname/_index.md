---
title: get_LocalName()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert de lokale naam van het knooppunt, wanneer overschreven in een afgeleide klasse.
type: docs
weight: 209
url: /nl/system.xml/xmlnode/get_localname/
---
## XmlNode::get_LocalName() methode


Retourneert de lokale naam van het knooppunt, wanneer overschreven in een afgeleide klasse.

```cpp
virtual String System::Xml::XmlNode::get_LocalName()=0
```


### Retourwaarde

De naam van het knooppunt zonder het voorvoegsel. Bijvoorbeeld, **LocalName** is **book** voor het element **<bk:book>**.
## Opmerkingen



De geretourneerde naam is afhankelijk van de [XmlNode::get_NodeType](../get_nodetype/) van het knooppunt: 

| Type | Naam |
| --- | --- |
| [Attribute](../../../system/attribute/)| De lokale naam van het attribuut. |
| CDATA | #cdata-section |
| Comment | #comment |
| Document | #document |
| DocumentFragment | #document-fragment |
| DocumentType | De naam van het documenttype. |
| Element | De lokale naam van het element. |
| Entity | De naam van de entiteit. |
| EntityReference | De naam van de verwezen entiteit. |
| Notation | De naam van de notatie. |
| ProcessingInstruction | Het doel van de verwerkingsinstructie. |
| [Text](../../../system.text/)| #text |
| Whitespace | #whitespace |
| SignificantWhitespace | #significant-whitespace |
| [XmlDeclaration](../../xmldeclaration/)| #xml-declaration |


## Zie ook

* Klasse [String](../../../system/string/)
* Klasse [XmlNode](../)
* Naamruimte [System::Xml](../../)
* Bibliotheek [Aspose.Slides](../../../)