---
title: InsertBefore()
second_title: Riferimento API di Aspose.Slides per C++
description: Inserisce l'attributo specificato immediatamente prima dell'attributo di riferimento specificato.
type: docs
weight: 53
url: /it/system.xml/xmlattributecollection/insertbefore/
---
## XmlAttributeCollection::InsertBefore(const SharedPtr\<XmlAttribute\>\&, const SharedPtr\<XmlAttribute\>\&) metodo


Inserisce l'attributo specificato immediatamente prima dell'attributo di riferimento specificato.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::InsertBefore(const SharedPtr<XmlAttribute> &newNode, const SharedPtr<XmlAttribute> &refNode)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newNode | const [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\>\& | L'attributo da inserire. |
| refNode | const [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\>\& | L'attributo di riferimento. **newNode** è posizionato prima di **refNode**. |

### Valore di ritorno

Il [XmlAttribute](../../xmlattribute/) da inserire nella collezione.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlAttribute](../../xmlattribute/)
* Classe [XmlAttributeCollection](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)