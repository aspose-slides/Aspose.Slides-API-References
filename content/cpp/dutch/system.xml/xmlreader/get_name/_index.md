---
title: get_Name()
second_title: Aspose.Slides voor C++ API Referentie
description: Wanneer overschreven in een afgeleide klasse, krijgt de gekwalificeerde naam van het huidige knooppunt.
type: docs
weight: 27
url: /nl/system.xml/xmlreader/get_name/
---
## XmlReader::get_Name() methode


Wanneer overschreven in een afgeleide klasse, krijgt de gekwalificeerde naam van het huidige knooppunt.

```cpp
virtual String System::Xml::XmlReader::get_Name()
```


### Retourwaarde

De gekwalificeerde naam van het huidige knooppunt. Bijvoorbeeld, **Name** is **bk:book** voor het element **<bk:book>**.
## Opmerkingen



De geretourneerde naam is afhankelijk van de [XmlReader::get_NodeType](../get_nodetype/)-waarde van het knooppunt. De volgende knooppunttypen geven de vermelde waarden terug. Alle andere knooppunttypen geven een lege string terug. 

| Knooppunttype | Naam |
| --- | --- |
| `[Attribute](../../../system/attribute/)`| De naam van het attribuut. |
| `DocumentType`| De documenttype naam. |
| `Element`| De tagnaam. |
| `EntityReference`| De naam van de gerefereerde entiteit. |
| `ProcessingInstruction`| Het doel van de verwerkingsinstructie. |
| [XmlDeclaration](../../xmldeclaration/)| De letterlijke tekenreeks `xml`. |


## Zie ook

* Klasse [String](../../../system/string/)
* Klasse [XmlReader](../)
* Naamruimte [System::Xml](../../)
* Bibliotheek [Aspose.Slides](../../../)