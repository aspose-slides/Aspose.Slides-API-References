---
title: get_Name()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert de gekwalificeerde naam van het huidige knooppunt.
type: docs
weight: 14
url: /nl/system.xml/xmltextreader/get_name/
---
## XmlTextReader::get_Name() methode


Retourneert de gekwalificeerde naam van het huidige knooppunt.

```cpp
String System::Xml::XmlTextReader::get_Name() override
```


### Retourwaarde

De gekwalificeerde naam van het huidige knooppunt. Bijvoorbeeld, **Name** is **bk:book** voor het element **<bk:book>**.
## Opmerkingen



De geretourneerde naam is afhankelijk van de [XmlTextReader::get_NodeType](../get_nodetype/) waarde van het knooppunt. De volgende knooppunttypen retourneren de genoemde waarden. Alle andere knooppunttypen retourneren een lege tekenreeks. 

| Knooppunttype | Naam |
| --- | --- |
| [Attribute](../../../system/attribute/)| De naam van het attribuut. |
| DocumentType| De naam van het documenttype. |
| Element| De naam van de tag. |
| EntityReference| De naam van de gerefereerde entity. |
| ProcessingInstruction| Het doel van de verwerkingsinstructie. |
| [XmlDeclaration](../../xmldeclaration/)| De letterlijke tekenreeks `xml`. |


## Zie ook

* Klasse [String](../../../system/string/)
* Klasse [XmlTextReader](../)
* Naamruimte [System::Xml](../../)
* Bibliotheek [Aspose.Slides](../../../)