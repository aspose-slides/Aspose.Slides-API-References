---
title: CloneNode()
second_title: Riferimento API Aspose.Slides per C++
description: Crea una copia duplicata di questo nodo.
type: docs
weight: 53
url: /it/system.xml/xmlcdatasection/clonenode/
---
## XmlCDataSection::CloneNode(bool) metodo

Crea una copia duplicata di questo nodo.

```cpp
SharedPtr<XmlNode> System::Xml::XmlCDataSection::CloneNode(bool deep) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| deep | **bool** | **true** per clonare ricorsivamente il sottoalbero sotto il nodo specificato; **false** per clonare solo il nodo stesso. Poiché i nodi CDATA non hanno figli, indipendentemente dall'impostazione del parametro, il nodo clonato includerà sempre il contenuto dei dati. |

### Valore di ritorno

Il nodo clonato.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlNode](../../xmlnode/)
* Classe [XmlCDataSection](../)
* Spazio dei nomi [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)