---
title: InsertAfter()
second_title: Riferimento API Aspose.Slides per C++
description: Inserisce il nodo specificato immediatamente dopo il nodo di riferimento specificato.
type: docs
weight: 222
url: /it/system.xml/xmlattribute/insertafter/
---
## XmlAttribute::InsertAfter(SharedPtr\<XmlNode\>, SharedPtr\<XmlNode\>) metodo

Inserisce il nodo specificato immediatamente dopo il nodo di riferimento specificato.

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttribute::InsertAfter(SharedPtr<XmlNode> newChild, SharedPtr<XmlNode> refChild) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | Il [XmlNode](../../xmlnode/) da inserire. |
| refChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | Il [XmlNode](../../xmlnode/) che è il nodo di riferimento. Il **newChild** è posizionato dopo il **refChild**. |

### Valore di ritorno

Il [XmlNode](../../xmlnode/) inserito.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlNode](../../xmlnode/)
* Classe [XmlAttribute](../)
* Spazio dei nomi [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)