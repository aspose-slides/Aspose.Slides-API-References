---
title: get_Name()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce il nome qualificato del nodo, quando sovrascritto in una classe derivata.
type: docs
weight: 1
url: /it/system.xml/xmlnode/get_name/
---
## XmlNode::get_Name() metodo


Restituisce il nome qualificato del nodo, quando sovrascritto in una classe derivata.

```cpp
virtual String System::Xml::XmlNode::get_Name()=0
```


### Valore di ritorno

Il nome qualificato del nodo.
## Osservazioni



Il nome restituito dipende dal [XmlNode::get_NodeType](../get_nodetype/) del nodo: 

| Tipo | Nome |
| --- | --- |
| [Attribute](../../../system/attribute/)| Il nome qualificato dell'attributo. |
| CDATA | #cdata-section |
| Comment | #comment |
| Document | #document |
| DocumentFragment | #document-fragment |
| DocumentType | Il nome del tipo di documento. |
| Element | Il nome qualificato dell'elemento. |
| Entity | Il nome dell'entità. |
| EntityReference | Il nome dell'entità di riferimento. |
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