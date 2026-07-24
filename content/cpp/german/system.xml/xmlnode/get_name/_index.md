---
title: get_Name()
second_title: Aspose.Slides für C++ API Referenz
description: Gibt den qualifizierten Namen des Knotens zurück, wenn er in einer abgeleiteten Klasse überschrieben wird.
type: docs
weight: 1
url: /de/system.xml/xmlnode/get_name/
---
## XmlNode::get_Name() Methode

Gibt den qualifizierten Namen des Knotens zurück, wenn er in einer abgeleiteten Klasse überschrieben wird.

```cpp
virtual String System::Xml::XmlNode::get_Name()=0
```

### Rückgabewert

Der qualifizierte Name des Knotens.

## Bemerkungen

Der zurückgegebene Name hängt vom [XmlNode::get_NodeType](../get_nodetype/) des Knotens ab: 

| Type | Name |
| --- | --- |
| [Attribute](../../../system/attribute/)| Der qualifizierte Name des Attributs. |
| CDATA | #cdata-section |
| Comment | #comment |
| Document | #document |
| DocumentFragment | #document-fragment |
| DocumentType | Der Name des Dokumenttyps. |
| Element | Der qualifizierte Name des Elements. |
| Entity | Der Name der Entität. |
| EntityReference | Der Name der referenzierten Entität. |
| Notation | Der Notationsname. |
| ProcessingInstruction | Das Ziel der Verarbeitungsanweisung. |
| [Text](../../../system.text/)| #text |
| Whitespace | #whitespace |
| SignificantWhitespace | #significant-whitespace |
| [XmlDeclaration](../../xmldeclaration/)| #xml-declaration |

## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [XmlNode](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)