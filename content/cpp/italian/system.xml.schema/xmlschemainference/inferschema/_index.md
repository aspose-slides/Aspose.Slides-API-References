---
title: InferSchema()
second_title: Riferimento API Aspose.Slides per C++
description: Deriva uno schema XML Schema Definition Language (XSD) dal documento XML contenuto nell'oggetto XmlReader specificato.
type: docs
weight: 66
url: /it/system.xml.schema/xmlschemainference/inferschema/
---
## XmlSchemaInference::InferSchema(const SharedPtr\<XmlReader\>\&) metodo

Inferisce uno schema XML [Schema](../../) Definition Language (XSD) dal documento XML contenuto nell'oggetto [XmlReader](../../../system.xml/xmlreader/) specificato.

```cpp
SharedPtr<XmlSchemaSet> System::Xml::Schema::XmlSchemaInference::InferSchema(const SharedPtr<XmlReader> &instanceDocument)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| instanceDocument | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Un oggetto [XmlReader](../../../system.xml/xmlreader/) contenente il documento XML dal quale inferire uno schema. |

### Valore di ritorno

Un oggetto [XmlSchemaSet](../../xmlschemaset/) contenente gli schemi inferiti.

## XmlSchemaInference::InferSchema(const SharedPtr\<XmlReader\>\&, SharedPtr\<XmlSchemaSet\>) metodo

Inferisce uno schema XML [Schema](../../) Definition Language (XSD) dal documento XML contenuto nell'oggetto [XmlReader](../../../system.xml/xmlreader/) specificato e affina lo schema inferito utilizzando uno schema esistente nell'oggetto [XmlSchemaSet](../../xmlschemaset/) specificato con lo stesso spazio dei nomi di destinazione.

```cpp
SharedPtr<XmlSchemaSet> System::Xml::Schema::XmlSchemaInference::InferSchema(const SharedPtr<XmlReader> &instanceDocument, SharedPtr<XmlSchemaSet> schemas)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| instanceDocument | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Un oggetto [XmlReader](../../../system.xml/xmlreader/) contenente il documento XML dal quale inferire uno schema. |
| schemas | [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaSet](../../xmlschemaset/)\> | Un oggetto [XmlSchemaSet](../../xmlschemaset/) contenente uno schema esistente utilizzato per affinare lo schema inferito. |

### Valore di ritorno

Un oggetto [XmlSchemaSet](../../xmlschemaset/) contenente gli schemi inferiti.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlSchemaSet](../../xmlschemaset/)
* Classe [XmlReader](../../../system.xml/xmlreader/)
* Classe [XmlSchemaInference](../)
* Spazio dei nomi [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)