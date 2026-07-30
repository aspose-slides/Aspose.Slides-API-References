---
title: ValidateEndElement()
second_title: Riferimento API di Aspose.Slides per C++
description: Verifica se il contenuto testuale dell'elemento è valido secondo il suo tipo di dati per gli elementi con contenuto semplice e verifica se il contenuto dell'elemento corrente è completo per gli elementi con contenuto complesso.
type: docs
weight: 209
url: /it/system.xml.schema/xmlschemavalidator/validateendelement/
---
## XmlSchemaValidator::ValidateEndElement(const SharedPtr\<XmlSchemaInfo\>\&) metodo

Verifica se il contenuto testuale dell'elemento è valido rispetto al suo tipo di dati per gli elementi con contenuto semplice e verifica se il contenuto dell'elemento corrente è completo per gli elementi con contenuto complesso.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateEndElement(const SharedPtr<XmlSchemaInfo> &schemaInfo)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | Un oggetto [XmlSchemaInfo](../../xmlschemainfo/) i cui proprietà vengono impostate al completamento della validazione dell'elemento. Questo parametro può essere **nullptr**. |

### Valore di ritorno

Il valore testuale tipizzato, analizzato, dell'elemento se l'elemento ha contenuto semplice.

## XmlSchemaValidator::ValidateEndElement(const SharedPtr\<XmlSchemaInfo\>\&, const SharedPtr\<Object\>\&) metodo

Verifica se il contenuto testuale dell'elemento specificato è valido rispetto al suo tipo di dati.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateEndElement(const SharedPtr<XmlSchemaInfo> &schemaInfo, const SharedPtr<Object> &typedValue)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | Un oggetto [XmlSchemaInfo](../../xmlschemainfo/) i cui proprietà vengono impostate al completamento della validazione del contenuto testuale dell'elemento. Questo parametro può essere **nullptr**. |
| typedValue | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Il contenuto testuale tipizzato dell'elemento. |

### Valore di ritorno

Il contenuto semplice tipizzato, analizzato, dell'elemento.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Object](../../../system/object/)
* Classe [XmlSchemaInfo](../../xmlschemainfo/)
* Classe [XmlSchemaValidator](../)
* Spazio dei nomi [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)