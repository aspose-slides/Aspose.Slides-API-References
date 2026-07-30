---
title: Schemas()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce una raccolta di tutti gli schemi XML Schema definition language (XSD) nel XmlSchemaSet.
type: docs
weight: 248
url: /it/system.xml.schema/xmlschemaset/schemas/
---
## XmlSchemaSet::Schemas() metodo

Restituisce una raccolta di tutti gli schemi XML [Schema](../../) definition language (XSD) presenti nel [XmlSchemaSet](../).

```cpp
SharedPtr<Collections::Generic::IList<SharedPtr<XmlSchema>>> System::Xml::Schema::XmlSchemaSet::Schemas()
```

### Valore di ritorno

Un oggetto IList contenente tutti gli schemi che sono stati aggiunti al [XmlSchemaSet](../). Se non sono stati aggiunti schemi al [XmlSchemaSet](../), viene restituita una raccolta vuota.

## XmlSchemaSet::Schemas(String) metodo

Restituisce una raccolta di tutti gli schemi XML [Schema](../../) definition language (XSD) nel [XmlSchemaSet](../) che appartengono allo spazio dei nomi specificato.

```cpp
SharedPtr<Collections::Generic::List<SharedPtr<XmlSchema>>> System::Xml::Schema::XmlSchemaSet::Schemas(String targetNamespace)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| targetNamespace | [String](../../../system/string/) | La proprietà **targetNamespace** dello schema. |

### Valore di ritorno

Un oggetto IList contenente tutti gli schemi che sono stati aggiunti al [XmlSchemaSet](../) che appartengono allo spazio dei nomi specificato. Se non sono stati aggiunti schemi al [XmlSchemaSet](../), viene restituita una raccolta vuota.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IList](../../../system.collections.generic/ilist/)
* Classe [XmlSchema](../../xmlschema/)
* Classe [XmlSchemaSet](../)
* Classe [List](../../../system.collections.generic/list/)
* Classe [String](../../../system/string/)
* Spazio dei nomi [System::Xml::Schema](../../)
* Libreria [Aspose.Slides](../../../)