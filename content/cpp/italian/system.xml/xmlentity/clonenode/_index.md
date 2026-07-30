---
title: CloneNode()
second_title: Riferimento API Aspose.Slides per C++
description: Crea una copia duplicata di questo nodo. I nodi Entity non possono essere clonati. L'esecuzione di questo metodo su un oggetto XmlEntity genera un'eccezione.
type: docs
weight: 170
url: /it/system.xml/xmlentity/clonenode/
---
## XmlEntity::CloneNode(bool) metodo

Crea una copia duplicata di questo nodo. I nodi Entity non possono essere clonati. L'esecuzione di questo metodo su un oggetto [XmlEntity](../) genera un'eccezione.

```cpp
SharedPtr<XmlNode> System::Xml::XmlEntity::CloneNode(bool deep) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| deep | **bool** | **true** per clonare ricorsivamente il sottoalbero sotto il nodo specificato; **false** per clonare solo il nodo stesso. |

### Valore restituito

Una copia del [XmlNode](../../xmlnode/) da cui è stato chiamato il metodo.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlNode](../../xmlnode/)
* Classe [XmlEntity](../)
* Spazio dei nomi [System::Xml](../../)
* Library [Aspose.Slides](../../../)