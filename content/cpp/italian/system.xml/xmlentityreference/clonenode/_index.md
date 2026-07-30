---
title: CloneNode()
second_title: Riferimento API Aspose.Slides per C++
description: Crea un duplicato di questo nodo.
type: docs
weight: 92
url: /it/system.xml/xmlentityreference/clonenode/
---
## XmlEntityReference::CloneNode(bool) metodo

Crea un duplicato di questo nodo.

```cpp
SharedPtr<XmlNode> System::Xml::XmlEntityReference::CloneNode(bool deep) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| deep | **bool** | **true** per clonare ricorsivamente il sottoalbero sotto il nodo specificato; **false** per clonare solo il nodo stesso. Per i nodi [XmlEntityReference](../), questo metodo restituisce sempre un nodo di riferimento entità senza figli. Il testo di sostituzione viene impostato quando il nodo viene inserito in un genitore. |

### Valore restituito

Il nodo clonato.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlNode](../../xmlnode/)
* Classe [XmlEntityReference](../)
* Spazio dei nomi [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)