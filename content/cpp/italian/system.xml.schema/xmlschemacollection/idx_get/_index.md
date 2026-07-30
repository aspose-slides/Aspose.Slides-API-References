---
title: idx_get()
second_title: Riferimento API Aspose.Slides per C++
description: Restituisce lo XmlSchema associato all'URI namespace fornito.
type: docs
weight: 53
url: /it/system.xml.schema/xmlschemacollection/idx_get/
---
## XmlSchemaCollection::idx_get(const String\&) metodo

Restituisce il [XmlSchema](../../xmlschema/) associato all'URI namespace fornito.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::idx_get(const String &ns)
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | L'URI namespace associato allo schema da restituire. Questo sarà tipicamente il **targetNamespace** dello schema. |

### Valore di ritorno

Il [XmlSchema](../../xmlschema/) associato all'URI namespace; **nullptr** se non esiste uno schema caricato associato al namespace fornito o se il namespace è associato a uno schema XDR.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlSchema](../../xmlschema/)
* Classe [String](../../../system/string/)
* Classe [XmlSchemaCollection](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)