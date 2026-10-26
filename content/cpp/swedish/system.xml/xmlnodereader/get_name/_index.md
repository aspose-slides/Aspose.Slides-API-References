---
title: get_Name()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar det kvalificerade namnet på den aktuella noden.
type: docs
weight: 14
url: /sv/system.xml/xmlnodereader/get_name/
---
## XmlNodeReader::get_Name() metod

Returnerar det kvalificerade namnet på den aktuella noden.

```cpp
String System::Xml::XmlNodeReader::get_Name() override
```

### Returvärde

Det kvalificerade namnet på den aktuella noden. Till exempel är **Name** **bk:book** för elementet **<bk:book>**.

## Anmärkningar

Det returnerade namnet beror på [XmlNodeReader::get_NodeType](../get_nodetype/)-värdet för noden. Följande nodtyper returnerar de listade värdena. Alla andra nodtyper returnerar en tom sträng.

| Nodtyp | Namn |
| --- | --- |
| [Attribute](../../../system/attribute/)| Attributets namn. |
| DocumentType| Dokumenttypens namn. |
| Element| Taggnamnet. |
| EntityReference| Namnet på den refererade entiteten. |
| ProcessingInstruction| Målet för processinstruktionen. |
| [XmlDeclaration](../../xmldeclaration/)| Den bokstavliga strängen `xml`. |

## Se också

* Klass [String](../../../system/string/)
* Klass [XmlNodeReader](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)