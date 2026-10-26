---
title: Add()
second_title: Riferimento API di Aspose.Slides per C++
description: Aggiunge lo schema individuato dall'URL fornito alla raccolta di schemi.
type: docs
weight: 40
url: /it/system.xml.schema/xmlschemacollection/add/
---
## XmlSchemaCollection::Add(const String\&, const String\&) metodo

Aggiunge lo schema individuato dall'URL fornito alla raccolta di schemi.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const String &ns, const String &uri)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | L'URI dello spazio dei nomi associato allo schema. Per gli schemi XML, tipicamente sarà il **targetNamespace**. |
| uri | const [String](../../../system/string/)\& | L'URL che specifica lo schema da caricare. |

### Valore di ritorno

Il [XmlSchema](../../xmlschema/) aggiunto alla raccolta di schemi; **nullptr** se lo schema aggiunto è uno schema XDR o se ci sono errori di compilazione nello schema.

## XmlSchemaCollection::Add(const String\&, const SharedPtr\<XmlReader\>\&) metodo

Aggiunge lo schema contenuto nel [XmlReader](../../../system.xml/xmlreader/) alla raccolta di schemi.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const String &ns, const SharedPtr<XmlReader> &reader)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | L'URI dello spazio dei nomi associato allo schema. Per gli schemi XML, tipicamente sarà il **targetNamespace**. |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | [XmlReader](../../../system.xml/xmlreader/) contenente lo schema da aggiungere. |

### Valore di ritorno

Il [XmlSchema](../../xmlschema/) aggiunto alla raccolta di schemi; **nullptr** se lo schema aggiunto è uno schema XDR o se ci sono errori di compilazione nello schema.

## XmlSchemaCollection::Add(const String\&, const SharedPtr\<XmlReader\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) metodo

Aggiunge lo schema contenuto nel [XmlReader](../../../system.xml/xmlreader/) alla raccolta di schemi. Il [XmlResolver](../../../system.xml/xmlresolver/) specificato è usato per risolvere eventuali risorse esterne.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const String &ns, const SharedPtr<XmlReader> &reader, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | L'URI dello spazio dei nomi associato allo schema. Per gli schemi XML, tipicamente sarà il **targetNamespace**. |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | [XmlReader](../../../system.xml/xmlreader/) contenente lo schema da aggiungere. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | Il [XmlResolver](../../../system.xml/xmlresolver/) usato per risolvere gli spazi dei nomi riferiti negli elementi **include** e **import** o nell'attributo **x-schema** (schemi XDR). Se è **nullptr**, i riferimenti esterni non vengono risolti. |

### Valore di ritorno

Il [XmlSchema](../../xmlschema/) aggiunto alla raccolta di schemi; **nullptr** se lo schema aggiunto è uno schema XDR o se ci sono errori di compilazione nello schema.

## XmlSchemaCollection::Add(const SharedPtr\<XmlSchema\>\&) metodo

Aggiunge il [XmlSchema](../../xmlschema/) alla raccolta.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const SharedPtr<XmlSchema> &schema)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | Il [XmlSchema](../../xmlschema/) da aggiungere alla raccolta. |

### Valore di ritorno

L'oggetto [XmlSchema](../../xmlschema/).

## XmlSchemaCollection::Add(const SharedPtr\<XmlSchema\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) metodo

Aggiunge il [XmlSchema](../../xmlschema/) alla raccolta. Il [XmlResolver](../../../system.xml/xmlresolver/) specificato è usato per risolvere eventuali riferimenti esterni.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const SharedPtr<XmlSchema> &schema, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | Il [XmlSchema](../../xmlschema/) da aggiungere alla raccolta. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | Il [XmlResolver](../../../system.xml/xmlresolver/) usato per risolvere gli spazi dei nomi riferiti negli elementi **include** e **import**. Se è **nullptr**, i riferimenti esterni non vengono risolti. |

### Valore di ritorno

Il [XmlSchema](../../xmlschema/) aggiunto alla raccolta di schemi.

## XmlSchemaCollection::Add(const SharedPtr\<XmlSchemaCollection\>\&) metodo

Aggiunge tutti gli spazi dei nomi definiti nella raccolta specificata (inclusi gli schemi associati) a questa raccolta.

```cpp
void System::Xml::Schema::XmlSchemaCollection::Add(const SharedPtr<XmlSchemaCollection> &schema)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaCollection](../)\>\& | Il [XmlSchemaCollection](../) che desideri aggiungere a questa raccolta. |

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../../xmlschema/)
* Class [String](../../../system/string/)
* Class [XmlSchemaCollection](../)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)