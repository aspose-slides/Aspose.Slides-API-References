---
title: CloneNode()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea una copia duplicata di questo nodo.
type: docs
weight: 79
url: /it/system.xml/xmlsignificantwhitespace/clonenode/
---
## XmlSignificantWhitespace::CloneNode(bool) method

Crea una copia duplicata di questo nodo.

```cpp
SharedPtr<XmlNode> System::Xml::XmlSignificantWhitespace::CloneNode(bool deep) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| deep | **bool** | **true** per clonare ricorsivamente il sottoalbero sotto il nodo specificato; **false** per clonare solo il nodo stesso. Per i nodi di spazi bianchi significativi, il nodo clonato include sempre il valore dei dati, indipendentemente dall’impostazione del parametro. |

### Valore restituito

Il nodo clonato.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlNode](../../xmlnode/)
* Classe [XmlSignificantWhitespace](../)
* Namespace [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)