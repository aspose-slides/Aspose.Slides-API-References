---
title: ValidateEndOfAttributes()
second_title: Aspose.Slides for C++ API Reference
description: Verifies whether all the required attributes in the element context are present and prepares the XmlSchemaValidator object to validate the child content of the element.
type: docs
weight: 170
url: /system.xml.schema/xmlschemavalidator/validateendofattributes/
---
## XmlSchemaValidator::ValidateEndOfAttributes(const SharedPtr\<XmlSchemaInfo\>&) method


Verifies whether all the required attributes in the element context are present and prepares the [XmlSchemaValidator](../) object to validate the child content of the element.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateEndOfAttributes(const SharedPtr<XmlSchemaInfo> &schemaInfo)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>& | An [XmlSchemaInfo](../../xmlschemainfo/) object whose properties are set on successful verification that all the required attributes in the element context are present. This parameter can be **nullptr**. |

### Exceptions

| Exception | Description |
| --- | --- |
| XmlSchemaValidationException | One or more of the required attributes in the current element context were not found. |
| InvalidOperationException | The [XmlSchemaValidator::ValidateEndOfAttributes](./) method was not called in the correct sequence. For example, calling [XmlSchemaValidator::ValidateEndOfAttributes](./) after calling [XmlSchemaValidator::SkipToEndElement](../skiptoendelement/). |
| ArgumentNullException | One or more of the parameters specified are **nullptr**. |


## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchemaInfo](../../xmlschemainfo/)
* Class [XmlSchemaValidator](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)