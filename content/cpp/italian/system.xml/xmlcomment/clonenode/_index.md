---
title: CloneNode()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea un duplicato di questo nodo.
type: docs
weight: 40
url: /it/system.xml/xmlcomment/clonenode/
---
## XmlComment::CloneNode(bool) metodo

Crea un duplicato di questo nodo.

```cpp
SharedPtr<XmlNode> System::Xml::XmlComment::CloneNode(bool deep) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| deep | **bool** | **true** per clonare ricorsivamente il sottoalbero sotto il nodo specificato; **false** per clonare solo il nodo stesso. Poiché i nodi commento non hanno figli, il nodo clonato include sempre il contenuto del testo, indipendentemente dall'impostazione del parametro. |

### Valore restituito

Il nodo clonato.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlNode](../../xmlnode/)
* Classe [XmlComment](../)
* Namespace [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)