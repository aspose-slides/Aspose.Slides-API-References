---
title: ValidateWhitespace()
second_title: Aspose.Slides for C++ API Reference
description: Validates whether the white space in the string specified is allowed in the current element context, and accumulates the white space for validation if the current element has simple content.
type: docs
weight: 196
url: /cpp/system.xml.schema/xmlschemavalidator/validatewhitespace/
---
## XmlSchemaValidator::ValidateWhitespace(const String\&) method


Validates whether the white space in the **string** specified is allowed in the current element context, and accumulates the white space for validation if the current element has simple content.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateWhitespace(const String &elementValue)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| elementValue | const [String](../../../system/string/)\& | A white space **string** to validate in the current element context. |

## XmlSchemaValidator::ValidateWhitespace(XmlValueGetter) method


Validates whether the white space returned by the XmlValueGetter object specified is allowed in the current element context, and accumulates the white space for validation if the current element has simple content.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateWhitespace(XmlValueGetter elementValue)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| elementValue | [XmlValueGetter](../../xmlvaluegetter/) | An XmlValueGetter callback used to pass the white space value as a type compatible with the XML [Schema](../../) Definition Language (XSD) type of the attribute. |

## See Also

* Typedef [XmlValueGetter](../../xmlvaluegetter/)
* Class [String](../../../system/string/)
* Class [XmlSchemaValidator](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)