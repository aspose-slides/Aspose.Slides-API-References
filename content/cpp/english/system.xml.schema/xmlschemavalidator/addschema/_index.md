---
title: AddSchema()
second_title: Aspose.Slides for C++ API Reference
description: Adds an XML Schema Definition Language (XSD) schema to the set of schemas used for validation.
type: docs
weight: 105
url: /system.xml.schema/xmlschemavalidator/addschema/
---
## XmlSchemaValidator::AddSchema(const SharedPtr\<XmlSchema\>&) method


Adds an XML [Schema](../../) Definition Language (XSD) schema to the set of schemas used for validation.

```cpp
void System::Xml::Schema::XmlSchemaValidator::AddSchema(const SharedPtr<XmlSchema> &schema)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>& | An [XmlSchema](../../xmlschema/) object to add to the set of schemas used for validation. |

### Exceptions

| Exception | Description |
| --- | --- |
| ArgumentNullException | The [XmlSchema](../../xmlschema/) parameter specified is **nullptr**. |
| XmlSchemaValidationException | The target namespace of the [XmlSchema](../../xmlschema/) parameter matches that of any element or attribute already encountered by the [XmlSchemaValidator](../) object. |
| XmlSchemaException | The [XmlSchema](../../xmlschema/) parameter is invalid. |


## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../../xmlschema/)
* Class [XmlSchemaValidator](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)