---
title: GetUnspecifiedDefaultAttributes()
second_title: Aspose.Slides for C++ API Reference
description: "Validates identity constraints on the default attributes and populates the List specified with XmlSchemaAttribute objects for any attributes with default values that have not been previously validated using the XmlSchemaValidator::ValidateAttribute method in the element context."
type: docs
weight: 157
url: /cpp/system.xml.schema/xmlschemavalidator/getunspecifieddefaultattributes/
---
## XmlSchemaValidator::GetUnspecifiedDefaultAttributes(const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::List](../../../system.collections.generic/list/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\>\>\&) method


Validates identity constraints on the default attributes and populates the List specified with [XmlSchemaAttribute](../../xmlschemaattribute/) objects for any attributes with default values that have not been previously validated using the [XmlSchemaValidator::ValidateAttribute](../validateattribute/) method in the element context.

```cpp
void System::Xml::Schema::XmlSchemaValidator::GetUnspecifiedDefaultAttributes(const SharedPtr<Collections::Generic::List<SharedPtr<Object>>> &defaultAttributes)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| defaultAttributes | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::List](../../../system.collections.generic/list/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\>\>\& | A List to populate with [XmlSchemaAttribute](../../xmlschemaattribute/) objects for any attributes not yet encountered during validation in the element context. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [List](../../../system.collections.generic/list/)
* Class [Object](../../../system/object/)
* Class [XmlSchemaValidator](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)
