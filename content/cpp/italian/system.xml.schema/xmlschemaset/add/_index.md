---
title: Add()
second_title: Aspose.Slides per C++ Riferimento API
description: Aggiunge lo schema del linguaggio di definizione XML Schema (XSD) all'URL specificato al XmlSchemaSet.
type: docs
weight: 157
url: /it/system.xml.schema/xmlschemaset/add/
---
## XmlSchemaSet::Add(String, const String\&) metodo


Aggiunge lo schema XML [Schema](../../) (linguaggio di definizione, XSD) all'URL specificato al [XmlSchemaSet](../).

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Add(String targetNamespace, const String &schemaUri)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| targetNamespace | [String](../../../system/string/) | Il valore **targetNamespace** dello schema, oppure **nullptr** per utilizzare il **targetNamespace** specificato nello schema. |
| schemaUri | const [String](../../../system/string/)\& | L'URL che specifica lo schema da caricare. |

### Valore di ritorno

Un oggetto [XmlSchema](../../xmlschema/) se lo schema è valido. Se lo schema non è valido e viene specificato un ValidationEventHandler, allora viene restituito **nullptr** e viene sollevato l'evento di validazione appropriato. Altrimenti, viene lanciata una XmlSchemaException.

## XmlSchemaSet::Add(String, const SharedPtr\<XmlReader\>\&) metodo


Aggiunge lo schema XML [Schema](../../) (linguaggio di definizione, XSD) contenuto in [XmlReader](../../../system.xml/xmlreader/) al [XmlSchemaSet](../).

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Add(String targetNamespace, const SharedPtr<XmlReader> &schemaDocument)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| targetNamespace | [String](../../../system/string/) | Il valore **targetNamespace** dello schema, oppure **nullptr** per utilizzare il **targetNamespace** specificato nello schema. |
| schemaDocument | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | L'oggetto [XmlReader](../../../system.xml/xmlreader/). |

### Valore di ritorno

Un oggetto [XmlSchema](../../xmlschema/) se lo schema è valido. Se lo schema non è valido e viene specificato un ValidationEventHandler, allora viene restituito **nullptr** e viene sollevato l'evento di validazione appropriato. Altrimenti, viene lanciata una XmlSchemaException.

## XmlSchemaSet::Add(const SharedPtr\<XmlSchemaSet\>\&) metodo


Aggiunge tutti gli schemi XML [Schema](../../) (linguaggio di definizione, XSD) presenti nel [XmlSchemaSet](../) fornito al [XmlSchemaSet](../).

```cpp
void System::Xml::Schema::XmlSchemaSet::Add(const SharedPtr<XmlSchemaSet> &schemas)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| schemas | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaSet](../)\>\& | L'oggetto [XmlSchemaSet](../). |

## XmlSchemaSet::Add(const SharedPtr\<XmlSchema\>\&) metodo


Aggiunge il [XmlSchema](../../xmlschema/) fornito al [XmlSchemaSet](../).

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Add(const SharedPtr<XmlSchema> &schema)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | L'oggetto [XmlSchema](../../xmlschema/) da aggiungere al [XmlSchemaSet](../). |

### Valore di ritorno

Un oggetto [XmlSchema](../../xmlschema/) se lo schema è valido. Se lo schema non è valido e viene specificato un ValidationEventHandler, allora viene restituito **nullptr** e viene sollevato l'evento di validazione appropriato. Altrimenti, viene lanciata una XmlSchemaException.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlSchema](../../xmlschema/)
* Classe [String](../../../system/string/)
* Classe [XmlSchemaSet](../)
* Classe [XmlReader](../../../system.xml/xmlreader/)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)