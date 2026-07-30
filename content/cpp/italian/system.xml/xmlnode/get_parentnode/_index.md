---
title: get_ParentNode()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce il nodo genitore di questo nodo (per i nodi che possono avere genitori).
type: docs
weight: 53
url: /it/system.xml/xmlnode/get_parentnode/
---
## XmlNode::get_ParentNode() metodo


Restituisce il nodo genitore di questo nodo (per i nodi che possono avere genitori).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNode::get_ParentNode() final
```


### Valore di ritorno

Il [XmlNode](../) che è il genitore del nodo corrente.

## Osservazioni

Se un nodo è appena stato creato e non è ancora stato aggiunto all'albero, o se è stato rimosso dall'albero, il genitore è **nullptr**. Per tutti gli altri nodi, il valore restituito dipende dal [XmlNode::get_NodeType](../get_nodetype/) del nodo. La tabella seguente descrive i possibili valori di ritorno per il **get_NodeType** metodo. 

| TipoNodo | Valore di ritorno di ParentNode |
| --- | --- |
| [Attribute](../../../system/attribute/), Document, DocumentFragment, Entity, Notation | Returns `nullptr`; these nodes do not have parents. |
| CDATA | Returns the element or entity reference containing the CDATA section. |
| Comment | Returns the element, entity reference, document type, or document containing the comment. |
| DocumentType | Returns the document node. |
| Element | Returns the parent node of the element. If the element is the root node in the tree, the parent is the document node. |
| EntityReference | Returns the element, attribute, or entity reference containing the entity reference. |
| ProcessingInstruction | Returns the document, element, document type, or entity reference containing the processing instruction. |
| [Text](../../../system.text/) | Returns the parent element, attribute, or entity reference containing the text node. |


## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlNode](../)
* Spazio dei nomi [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)