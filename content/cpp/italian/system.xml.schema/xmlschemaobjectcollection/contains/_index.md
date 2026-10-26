---
title: Contains()
second_title: Riferimento API di Aspose.Slides per C++
description: Indica se lo XmlSchemaObject specificato è presente nella XmlSchemaObjectCollection.
type: docs
weight: 92
url: /it/system.xml.schema/xmlschemaobjectcollection/contains/
---
## XmlSchemaObjectCollection::Contains(const SharedPtr\<XmlSchemaObject\>\&) method

Indica se il [XmlSchemaObject](../../xmlschemaobject/) specificato è presente nel [XmlSchemaObjectCollection](../).

```cpp
bool System::Xml::Schema::XmlSchemaObjectCollection::Contains(const SharedPtr<XmlSchemaObject> &item)
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| item | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaObject](../../xmlschemaobject/)\>\& | Il [XmlSchemaObject](../../xmlschemaobject/). |

### Valore di ritorno

**true** se il nome qualificato specificato è nella raccolta; altrimenti, restituisce **false**. Se viene fornito **nullptr**, viene restituito **false** perché non esiste alcun nome qualificato con un nome nullo.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchemaObject](../../xmlschemaobject/)
* Class [XmlSchemaObjectCollection](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)