---
title: get_Name()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar det kvalificerade namnet på den aktuella noden.
type: docs
weight: 14
url: /sv/system.xml/xmltextreader/get_name/
---
## XmlTextReader::get_Name() metod

Returnerar det kvalificerade namnet på den aktuella noden.

```cpp
String System::Xml::XmlTextReader::get_Name() override
```

### Returvärde

Det kvalificerade namnet på den aktuella noden. Till exempel är **Name** **bk:book** för elementet **<bk:book>**.

## Anmärkningar

Namnet som returneras beror på värdet [XmlTextReader::get_NodeType](../get_nodetype/) för noden. Följande nodtyper returnerar de listade värdena. Alla andra nodtyper returnerar en tom sträng. 

| Nodtyp | Namn |
| --- | --- |
| [Attribute](../../../system/attribute/)| Namnet på attributet. |
| DocumentType| Dokumenttypens namn. |
| Element| Taggnamnet. |
| EntityReference| Namnet på den refererade entiteten. |
| ProcessingInstruction| Målet för processinstruktionen. |
| [XmlDeclaration](../../xmldeclaration/)| Den bokstavliga strängen `xml`. |

## Se även

* Klass [String](../../../system/string/)
* Klass [XmlTextReader](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)