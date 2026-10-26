---
title: get_LocalName()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt den lokalen Namen des Knotens zurück, wenn er in einer abgeleiteten Klasse überschrieben wird.
type: docs
weight: 209
url: /de/system.xml/xmlnode/get_localname/
---
## XmlNode::get_LocalName() Methode

Gibt den lokalen Namen des Knotens zurück, wenn er in einer abgeleiteten Klasse überschrieben wird.

```cpp
virtual String System::Xml::XmlNode::get_LocalName()=0
```

### Rückgabewert

Der Name des Knotens ohne das Präfix. Zum Beispiel ist **LocalName** **book** für das Element **<bk:book>**.

## Anmerkungen

Der zurückgegebene Name hängt vom [XmlNode::get_NodeType](../get_nodetype/) des Knotens ab:

| Typ | Name |
| --- | --- |
| [Attribute](../../../system/attribute/)| Der lokale Name des Attributs. |
| CDATA | #cdata-section |
| Comment | #comment |
| Document | #document |
| DocumentFragment | #document-fragment |
| DocumentType | Der Dokumenttyp-Name. |
| Element | Der lokale Name des Elements. |
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