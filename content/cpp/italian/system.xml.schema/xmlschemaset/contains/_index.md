---
title: Contains()
second_title: Riferimento API di Aspose.Slides per C++
description: Indica se uno schema del linguaggio di definizione XML Schema (XSD) con lo specificato URI dello spazio dei nomi di destinazione è presente nel XmlSchemaSet.
type: docs
weight: 196
url: /it/system.xml.schema/xmlschemaset/contains/
---
## XmlSchemaSet::Contains(String) metodo

Indica se uno schema di linguaggio di definizione XML [Schema](../../) (XSD) con lo specificato URI dello spazio dei nomi di destinazione è presente nel [XmlSchemaSet](../).

```cpp
bool System::Xml::Schema::XmlSchemaSet::Contains(String targetNamespace)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| targetNamespace | [String](../../../system/string/) | La proprietà **targetNamespace** dello schema. |

### Valore restituito

**true** se uno schema con lo specificato URI dello spazio dei nomi di destinazione è presente nel [XmlSchemaSet](../); altrimenti, **false**.

## XmlSchemaSet::Contains(const SharedPtr\<XmlSchema\>\&) metodo

Indica se l'oggetto [XmlSchema](../../xmlschema/) del linguaggio di definizione XML [Schema](../../) (XSD) specificato è presente nel [XmlSchemaSet](../).

```cpp
bool System::Xml::Schema::XmlSchemaSet::Contains(const SharedPtr<XmlSchema> &schema)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | L'oggetto [XmlSchema](../../xmlschema/). |

### Valore restituito

**true** se l'oggetto [XmlSchema](../../xmlschema/) è presente nel [XmlSchemaSet](../); altrimenti, **false**.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [String](../../../system/string/)
* Classe [XmlSchemaSet](../)
* Classe [XmlSchema](../../xmlschema/)
* Spazio dei nomi [System::Xml::Schema](../../)
* Libreria [Aspose.Slides](../../../)