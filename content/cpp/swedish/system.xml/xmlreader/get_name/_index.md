---
title: get_Name()
second_title: Aspose.Slides för C++ API-referens
description: När den åsidosätts i en avledd klass, får den det kvalificerade namnet på den aktuella noden.
type: docs
weight: 27
url: /sv/system.xml/xmlreader/get_name/
---
## XmlReader::get_Name() method


När den åsidosätts i en avledd klass, får den det kvalificerade namnet på den aktuella noden.

```cpp
virtual String System::Xml::XmlReader::get_Name()
```


### Return Value

Det kvalificerade namnet på den aktuella noden. Till exempel är **Name** **bk:book** för elementet **<bk:book>**.

## Anmärkningar



Det returnerade namnet beror på [XmlReader::get_NodeType](../get_nodetype/)-värdet för noden. Följande nodtyper returnerar de angivna värdena. Alla andra nodtyper returnerar en tom sträng. 

| Nodtyp | Namn |
| --- | --- |
| `[Attribute](../../../system/attribute/)`| Attributets namn. |
| `DocumentType`| Dokumenttypens namn. |
| `Element`| Taggnamnet. |
| `EntityReference`| Namnet på den refererade entiteten. |
| `ProcessingInstruction`| Målet för processinstruktionen. |
| [XmlDeclaration](../../xmldeclaration/)| Den bokstavliga strängen `xml`. |


## Se även

* Klass [String](../../../system/string/)
* Klass [XmlReader](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)