---
title: CloneNode()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea un duplicato di questo nodo.
type: docs
weight: 118
url: /it/system.xml/xmldocumenttype/clonenode/
---
## XmlDocumentType::CloneNode(bool) metodo

Crea un duplicato di questo nodo.

```cpp
SharedPtr<XmlNode> System::Xml::XmlDocumentType::CloneNode(bool deep) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| deep | **bool** | **true** per clonare ricorsivamente il sottoalbero sotto il nodo specificato; **false** per clonare solo il nodo stesso. Per i nodi di tipo documento, il nodo clonato include sempre il sottoalbero, indipendentemente dall'impostazione del parametro. |

### Valore restituito

Il nodo clonato.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlNode](../../xmlnode/)
* Classe [XmlDocumentType](../)
* Spazio dei nomi [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)