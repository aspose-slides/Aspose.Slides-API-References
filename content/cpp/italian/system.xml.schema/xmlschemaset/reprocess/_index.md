---
title: Reprocess()
second_title: Aspose.Slides per C++ Riferimento API
description: Rielabora uno schema XML Schema definition language (XSD) già presente nel XmlSchemaSet.
type: docs
weight: 222
url: /it/system.xml.schema/xmlschemaset/reprocess/
---
## XmlSchemaSet::Reprocess(SharedPtr\<XmlSchema\>) metodo


Rielabora uno schema XML [Schema](../../) definition language (XSD) già presente nel [XmlSchemaSet](../).

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Reprocess(SharedPtr<XmlSchema> schema)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| schema | [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\> | Lo schema da rielaborare. |

### Valore restituito

Un oggetto [XmlSchema](../../xmlschema/) se lo schema è uno schema valido. Se lo schema non è valido e viene specificato un ValidationEventHandler, **nullptr** è restituito e viene sollevato l'evento di validazione appropriato. Altrimenti, viene generata un'eccezione XmlSchemaException.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlSchema](../../xmlschema/)
* Classe [XmlSchemaSet](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)