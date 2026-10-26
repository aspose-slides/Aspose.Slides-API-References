---
title: GetUnspecifiedDefaultAttributes()
second_title: Riferimento API di Aspose.Slides per C++
description: "Convalida i vincoli di identità sugli attributi predefiniti e popola la List specificata con gli oggetti XmlSchemaAttribute per tutti gli attributi con valori predefiniti che non sono stati precedentemente convalidati utilizzando il metodo XmlSchemaValidator::ValidateAttribute nel contesto dell'elemento."
type: docs
weight: 157
url: /it/system.xml.schema/xmlschemavalidator/getunspecifieddefaultattributes/
---
## XmlSchemaValidator::GetUnspecifiedDefaultAttributes(const SharedPtr\<Collections::Generic::List\<SharedPtr\<Object\>\>\>\&) metodo

Convalida i vincoli di identità sugli attributi predefiniti e popola la List specificata con gli oggetti [XmlSchemaAttribute](../../xmlschemaattribute/) per tutti gli attributi con valori predefiniti che non sono stati precedentemente convalidati utilizzando il metodo [XmlSchemaValidator::ValidateAttribute](../validateattribute/) nel contesto dell'elemento.

```cpp
void System::Xml::Schema::XmlSchemaValidator::GetUnspecifiedDefaultAttributes(const SharedPtr<Collections::Generic::List<SharedPtr<Object>>> &defaultAttributes)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| defaultAttributes | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::List](../../../system.collections.generic/list/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\>\>\& | Una List da popolare con gli oggetti [XmlSchemaAttribute](../../xmlschemaattribute/) per tutti gli attributi non ancora incontrati durante la convalida nel contesto dell'elemento. |

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [List](../../../system.collections.generic/list/)
* Class [Object](../../../system/object/)
* Class [XmlSchemaValidator](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)