---
title: ValidateElement()
second_title: Riferimento API Aspose.Slides per C++
description: Convalida l'elemento nel contesto corrente.
type: docs
weight: 131
url: /it/system.xml.schema/xmlschemavalidator/validateelement/
---
## XmlSchemaValidator::ValidateElement(const String\&, const String\&, const SharedPtr\<XmlSchemaInfo\>\&) metodo


Convalida l'elemento nel contesto corrente.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateElement(const String &localName, const String &namespaceUri, const SharedPtr<XmlSchemaInfo> &schemaInfo)
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Il nome locale dell'elemento da convalidare. |
| namespaceUri | const [String](../../../system/string/)\& | L'URI del namespace dell'elemento da convalidare. |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | Un oggetto [XmlSchemaInfo](../../xmlschemainfo/) le cui proprietà vengono impostate al termine con successo della convalida del nome dell'elemento. Questo parametro può essere **nullptr**. |

## XmlSchemaValidator::ValidateElement(const String\&, const String\&, const SharedPtr\<XmlSchemaInfo\>\&, const String\&, const String\&, const String\&, const String\&) metodo


Convalida l'elemento nel contesto corrente con i valori degli attributi **xsi:Type**, **xsi:Nil**, **xsi:SchemaLocation** e **xsi:NoNamespaceSchemaLocation** specificati.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateElement(const String &localName, const String &namespaceUri, const SharedPtr<XmlSchemaInfo> &schemaInfo, const String &xsiType, const String &xsiNil, const String &xsiSchemaLocation, const String &xsiNoNamespaceSchemaLocation)
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Il nome locale dell'elemento da convalidare. |
| namespaceUri | const [String](../../../system/string/)\& | L'URI del namespace dell'elemento da convalidare. |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | Un oggetto [XmlSchemaInfo](../../xmlschemainfo/) le cui proprietà vengono impostate al termine con successo della convalida del nome dell'elemento. Questo parametro può essere **nullptr**. |
| xsiType | const [String](../../../system/string/)\& | Il valore dell'attributo **xsi:Type** dell'elemento. Questo parametro può essere **nullptr**. |
| xsiNil | const [String](../../../system/string/)\& | Il valore dell'attributo **xsi:Nil** dell'elemento. Questo parametro può essere **nullptr**. |
| xsiSchemaLocation | const [String](../../../system/string/)\& | Il valore dell'attributo **xsi:SchemaLocation** dell'elemento. Questo parametro può essere **nullptr**. |
| xsiNoNamespaceSchemaLocation | const [String](../../../system/string/)\& | Il valore dell'attributo **xsi:NoNamespaceSchemaLocation** dell'elemento. Questo parametro può essere **nullptr**. |

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [String](../../../system/string/)
* Classe [XmlSchemaInfo](../../xmlschemainfo/)
* Classe [XmlSchemaValidator](../)
* Spazio dei nomi [System::Xml::Schema](../../)
* Libreria [Aspose.Slides](../../../)