---
title: get_Name()
second_title: Aspose.Slides voor C++ API-documentatie
description: Retourneert de gekwalificeerde naam van het huidige knooppunt.
type: docs
weight: 14
url: /nl/system.xml/xmlvalidatingreader/get_name/
---
## XmlValidatingReader::get_Name() method


Retourneert de gekwalificeerde naam van het huidige knooppunt.

```cpp
String System::Xml::XmlValidatingReader::get_Name() override
```


### Retourwaarde

De gekwalificeerde naam van het huidige knooppunt. Bijvoorbeeld, **Name** is **bk:book** voor het element **<bk:book>**.
## Opmerkingen



De geretourneerde naam hangt af van de XmlValidatingReader::NodeType van het knooppunt. De volgende knooppunttypes geven de vermelde waarden terug. Alle andere knooppunttypes geven een lege tekenreeks terug. 

| Knooppunttype | Naam |
| --- | --- |
| [Attribute](../../../system/attribute/)| De naam van het attribuut. |
| DocumentType| De naam van het documenttype. |
| Element| De tagnaam. |
| EntityReference| De naam van de gerefereerde entiteit. |
| ProcessingInstruction| Het doel van de verwerkinginstructie. |
| [XmlDeclaration](../../xmldeclaration/)| De letterlijke tekenreeks `xml`. |


## Zie Ook

* Klasse [String](../../../system/string/)
* Klasse [XmlValidatingReader](../)
* Naamruimte [System::Xml](../../)
* Library [Aspose.Slides](../../../)