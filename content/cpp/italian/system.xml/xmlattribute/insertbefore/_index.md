---
title: InsertBefore()
second_title: Riferimento API Aspose.Slides per C++
description: Inserisce il nodo specificato immediatamente prima del nodo di riferimento specificato.
type: docs
weight: 209
url: /it/system.xml/xmlattribute/insertbefore/
---
## XmlAttribute::InsertBefore(SharedPtr\<XmlNode\>, SharedPtr\<XmlNode\>) metodo

Inserisce il nodo specificato immediatamente prima del nodo di riferimento specificato.

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttribute::InsertBefore(SharedPtr<XmlNode> newChild, SharedPtr<XmlNode> refChild) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | Il [XmlNode](../../xmlnode/) da inserire. |
| refChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | Il [XmlNode](../../xmlnode/) che è il nodo di riferimento. Il **newChild** è posizionato prima di questo nodo. |

### Valore di ritorno

Il [XmlNode](../../xmlnode/) inserito.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlNode](../../xmlnode/)
* Classe [XmlAttribute](../)
* Spazio dei nomi [System::Xml](../../)
* Library [Aspose.Slides](../../../)