---
title: ValidateAttribute()
second_title: Riferimento API Aspose.Slides per C++
description: Convalida il nome dell'attributo, l'URI dello spazio dei nomi e il valore nel contesto dell'elemento corrente.
type: docs
weight: 144
url: /it/system.xml.schema/xmlschemavalidator/validateattribute/
---
## XmlSchemaValidator::ValidateAttribute(const String\&, const String\&, const String\&, const SharedPtr\<XmlSchemaInfo\>\&) metodo


Convalida il nome dell'attributo, l'URI dello spazio dei nomi e il valore nel contesto dell'elemento corrente.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateAttribute(const String &localName, const String &namespaceUri, const String &attributeValue, const SharedPtr<XmlSchemaInfo> &schemaInfo)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Il nome locale dell'attributo da convalidare. |
| namespaceUri | const [String](../../../system/string/)\& | L'URI dello spazio dei nomi dell'attributo da convalidare. |
| attributeValue | const [String](../../../system/string/)\& | Il valore dell'attributo da convalidare. |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | Un oggetto [XmlSchemaInfo](../../xmlschemainfo/) le cui proprietà vengono impostate al completamento con successo della convalida dell'attributo. Questo parametro può essere **nullptr**. |

### Valore restituito

Il valore dell'attributo convalidato.

## XmlSchemaValidator::ValidateAttribute(const String\&, const String\&, XmlValueGetter, const SharedPtr\<XmlSchemaInfo\>\&) metodo


Convalida il nome dell'attributo, l'URI dello spazio dei nomi e il valore nel contesto dell'elemento corrente.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateAttribute(const String &localName, const String &namespaceUri, XmlValueGetter attributeValue, const SharedPtr<XmlSchemaInfo> &schemaInfo)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Il nome locale dell'attributo da convalidare. |
| namespaceUri | const [String](../../../system/string/)\& | L'URI dello spazio dei nomi dell'attributo da convalidare. |
| attributeValue | [XmlValueGetter](../../xmlvaluegetter/) | Una callback XmlValueGetter usata per passare il valore dell'attributo come tipo compatibile con il tipo XML [Schema](../../) Definition Language (XSD) dell'attributo. |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | Un oggetto [XmlSchemaInfo](../../xmlschemainfo/) le cui proprietà vengono impostate al completamento con successo della convalida dell'attributo. Questo parametro può essere **nullptr**. |

### Valore restituito

Il valore dell'attributo convalidato.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [XmlValueGetter](../../xmlvaluegetter/)
* Classe [Object](../../../system/object/)
* Classe [String](../../../system/string/)
* Classe [XmlSchemaInfo](../../xmlschemainfo/)
* Classe [XmlSchemaValidator](../)
* Spazio dei nomi [System::Xml::Schema](../../)
* Libreria [Aspose.Slides](../../../)