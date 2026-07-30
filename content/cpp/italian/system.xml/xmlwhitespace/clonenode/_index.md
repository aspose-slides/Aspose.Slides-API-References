---
title: CloneNode()
second_title: Riferimento API Aspose.Slides per C++
description: Crea un duplicato di questo nodo.
type: docs
weight: 79
url: /it/system.xml/xmlwhitespace/clonenode/
---
## XmlWhitespace::CloneNode(bool) metodo

Crea un duplicato di questo nodo.

```cpp
SharedPtr<XmlNode> System::Xml::XmlWhitespace::CloneNode(bool deep) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| deep | **bool** | **true** per clonare ricorsivamente il sottoalbero sotto il nodo specificato; **false** per clonare solo il nodo stesso. Per i nodi di spazio bianco, il nodo clonato include sempre il valore dei dati, indipendentemente dall'impostazione del parametro. |

### Valore restituito

Il nodo clonato.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlNode](../../xmlnode/)
* Classe [XmlWhitespace](../)
* Spazio dei nomi [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)