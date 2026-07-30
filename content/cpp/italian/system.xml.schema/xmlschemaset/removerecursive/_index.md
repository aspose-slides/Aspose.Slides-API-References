---
title: RemoveRecursive()
second_title: Riferimento API Aspose.Slides per C++
description: Rimuove lo schema XML Schema definition language (XSD) specificato e tutti gli schemi che esso importa dal XmlSchemaSet.
type: docs
weight: 183
url: /it/system.xml.schema/xmlschemaset/removerecursive/
---
## XmlSchemaSet::RemoveRecursive(const SharedPtr\<XmlSchema\>\&) method


Rimuove lo schema XML [Schema](../../) (XSD) specificato e tutti gli schemi che esso importa dal [XmlSchemaSet](../).

```cpp
bool System::Xml::Schema::XmlSchemaSet::RemoveRecursive(const SharedPtr<XmlSchema> &schemaToRemove)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| schemaToRemove | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | L'oggetto [XmlSchema](../../xmlschema/) da rimuovere dal [XmlSchemaSet](../). |

### Valore di ritorno

**true** se l'oggetto [XmlSchema](../../xmlschema/) e tutti i suoi import sono stati rimossi correttamente; altrimenti, **false**.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlSchema](../../xmlschema/)
* Classe [XmlSchemaSet](../)
* Spazio dei nomi [System::Xml::Schema](../../)
* Libreria [Aspose.Slides](../../../)