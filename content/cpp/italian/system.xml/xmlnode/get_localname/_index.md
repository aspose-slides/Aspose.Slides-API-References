---
title: get_LocalName()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce il nome locale del nodo, quando è sovrascritto in una classe derivata.
type: docs
weight: 209
url: /it/system.xml/xmlnode/get_localname/
---
## XmlNode::get_LocalName() metodo

Restituisce il nome locale del nodo, quando è sovrascritto in una classe derivata.

```cpp
virtual String System::Xml::XmlNode::get_LocalName()=0
```

### Valore restituito

Il nome del nodo con il prefisso rimosso. Per esempio, **LocalName** è **book** per l'elemento **<bk:book>**.

## Note

Il nome restituito dipende dal [XmlNode::get_NodeType](../get_nodetype/) del nodo:

| Tipo | Nome |
| --- | --- |
| [Attribute](../../../system/attribute/)| Il nome locale dell'attributo. |
| CDATA | #cdata-section |
| Comment | #comment |
| Document | #document |
| DocumentFragment | #document-fragment |
| DocumentType | Il nome del tipo di documento. |
| Element | Il nome locale dell'elemento. |
| Entity | Il nome dell'entità. |
| EntityReference | Il nome dell'entità referenziata. |
| Notation | Il nome della notazione. |
| ProcessingInstruction | Il target dell'istruzione di elaborazione. |
| [Text](../../../system.text/)| #text |
| Whitespace | #whitespace |
| SignificantWhitespace | #significant-whitespace |
| [XmlDeclaration](../../xmldeclaration/)| #xml-declaration |

## Vedi anche

* Classe [String](../../../system/string/)
* Classe [XmlNode](../)
* Spazio dei nomi [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)