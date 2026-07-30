---
title: Contains()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce un valore che indica se il targetNamespace dello XmlSchema specificato è nella collezione.
type: docs
weight: 66
url: /it/system.xml.schema/xmlschemacollection/contains/
---
## XmlSchemaCollection::Contains(const SharedPtr\<XmlSchema\>\&) method


Restituisce un valore che indica se il **targetNamespace** del [XmlSchema](../../xmlschema/) specificato è nella collezione.

```cpp
bool System::Xml::Schema::XmlSchemaCollection::Contains(const SharedPtr<XmlSchema> &schema)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | L'oggetto [XmlSchema](../../xmlschema/). |

### Valore di ritorno

**true** se esiste uno schema nella collezione con lo stesso **targetNamespace**; altrimenti, **false**.

## XmlSchemaCollection::Contains(const String\&) method


Restituisce un valore che indica se uno schema con lo spazio dei nomi specificato è nella collezione.

```cpp
bool System::Xml::Schema::XmlSchemaCollection::Contains(const String &ns)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | L'URI dello spazio dei nomi associato allo schema. Per gli XML Schema, questo sarà tipicamente lo spazio dei nomi di destinazione. |

### Valore di ritorno

**true** se uno schema con lo spazio dei nomi specificato è nella collezione; altrimenti, **false**.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlSchema](../../xmlschema/)
* Classe [XmlSchemaCollection](../)
* Classe [String](../../../system/string/)
* Spazio dei nomi [System::Xml::Schema](../../)
* Libreria [Aspose.Slides](../../../)