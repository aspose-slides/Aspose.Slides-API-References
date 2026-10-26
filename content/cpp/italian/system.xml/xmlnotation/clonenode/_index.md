---
title: CloneNode()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea una copia duplicata di questo nodo. I nodi di notazione non possono essere clonati. Chiamare questo metodo su un oggetto XmlNotation genera un'eccezione.
type: docs
weight: 118
url: /it/system.xml/xmlnotation/clonenode/
---
## XmlNotation::CloneNode(bool) metodo

Crea una copia duplicata di questo nodo. I nodi di notazione non possono essere clonati. Chiamare questo metodo su un oggetto [XmlNotation](../) genera un'eccezione.

```cpp
SharedPtr<XmlNode> System::Xml::XmlNotation::CloneNode(bool deep) override
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| deep | **bool** | **true** per clonare ricorsivamente il sottoalbero sotto il nodo specificato; **false** per clonare solo il nodo stesso. |

### Valore di ritorno

Una copia [XmlNode](../../xmlnode/) del nodo dal quale è chiamato il metodo.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlNode](../../xmlnode/)
* Classe [XmlNotation](../)
* Spazio dei nomi [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)