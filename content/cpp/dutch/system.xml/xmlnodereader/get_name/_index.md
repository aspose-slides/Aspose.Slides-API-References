---
title: get_Name()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert de gekwalificeerde naam van het huidige knooppunt.
type: docs
weight: 14
url: /nl/system.xml/xmlnodereader/get_name/
---
## XmlNodeReader::get_Name() methode


Retourneert de gekwalificeerde naam van het huidige knooppunt.

```cpp
String System::Xml::XmlNodeReader::get_Name() override
```


### Retourwaarde

De gekwalificeerde naam van het huidige knooppunt. Bijvoorbeeld, **Name** is **bk:book** voor het element **<bk:book>**.
## Opmerkingen



De geretourneerde naam is afhankelijk van de [XmlNodeReader::get_NodeType](../get_nodetype/)-waarde van het knooppunt. De volgende knooppunt-typen geven de vermelde waarden terug. Alle andere knooppunt-typen geven een lege tekenreeks terug. 

| Knooppunttype | Naam |
| --- | --- |
| [Attribute](../../../system/attribute/)| De naam van het attribuut. |
| DocumentType| De naam van het documenttype. |
| Element| De tag-naam. |
| EntityReference| De naam van de geraadpleegde entiteit. |
| ProcessingInstruction| Het doel van de verwerkingsinstructie. |
| [XmlDeclaration](../../xmldeclaration/)| De letterlijke tekenreeks `xml`. |


## Zie ook

* Klasse [String](../../../system/string/)
* Klasse [XmlNodeReader](../)
* Naamruimte [System::Xml](../../)
* Bibliotheek [Aspose.Slides](../../../)