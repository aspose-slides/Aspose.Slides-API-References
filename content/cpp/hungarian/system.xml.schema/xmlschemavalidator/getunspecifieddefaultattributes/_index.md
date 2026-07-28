---
title: GetUnspecifiedDefaultAttributes()
second_title: Aspose.Slides C++ API Referencia
description: "Érvényesíti az identitáskorlátokat az alapértelmezett attribútumokon, és feltölti a megadott List-et XmlSchemaAttribute objektumokkal minden olyan attribútumhoz, amelyek alapértelmezett értéke még nem lett korábban érvényesítve a XmlSchemaValidator::ValidateAttribute metódus használatával az elem kontextusában."
type: docs
weight: 157
url: /hu/system.xml.schema/xmlschemavalidator/getunspecifieddefaultattributes/
---
## XmlSchemaValidator::GetUnspecifiedDefaultAttributes(const SharedPtr\<Collections::Generic::List\<SharedPtr\<Object\>\>\>\&) metódus


Érvényesíti az identitáskorlátokat az alapértelmezett attribútumokon, és feltölti a List-et a [XmlSchemaAttribute](../../xmlschemaattribute/) objektumokkal minden olyan attribútumhoz, amelynek alapértelmezett értéke még nem volt korábban érvényesítve a [XmlSchemaValidator::ValidateAttribute](../validateattribute/) metódus használatával az elem kontextusában.

```cpp
void System::Xml::Schema::XmlSchemaValidator::GetUnspecifiedDefaultAttributes(const SharedPtr<Collections::Generic::List<SharedPtr<Object>>> &defaultAttributes)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| defaultAttributes | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::List](../../../system.collections.generic/list/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\>\>\& | A List-et a [XmlSchemaAttribute](../../xmlschemaattribute/) objektumokkal tölti fel minden olyan attribútumhoz, amely még nem került találatra az elem kontextusában történő érvényesítés során. |

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [List](../../../system.collections.generic/list/)
* Osztály [Object](../../../system/object/)
* Osztály [XmlSchemaValidator](../)
* Névtér [System::Xml::Schema](../../)
* Könyvtár [Aspose.Slides](../../../)