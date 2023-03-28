---
title: ValidateText()
second_title: Aspose.Slides for C++ API Reference
description: Validates whether the text string specified is allowed in the current element context, and accumulates the text for validation if the current element has simple content.
type: docs
weight: 183
url: /cpp/system.xml.schema/xmlschemavalidator/validatetext/
---
## XmlSchemaValidator::ValidateText(const [String](../../../system/string/)\&) method


Validates whether the text **string** specified is allowed in the current element context, and accumulates the text for validation if the current element has simple content.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateText(const String &elementValue)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| elementValue | const [String](../../../system/string/)\& | A text **string** to validate in the current element context. |

## See Also

* Class [String](../../../system/string/)
* Class [XmlSchemaValidator](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)
## XmlSchemaValidator::ValidateText([XmlValueGetter](../../xmlvaluegetter/)) method


Validates whether the text returned by the XmlValueGetter object specified is allowed in the current element context, and accumulates the text for validation if the current element has simple content.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateText(XmlValueGetter elementValue)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| elementValue | [XmlValueGetter](../../xmlvaluegetter/) | An XmlValueGetter callback used to pass the text value as a type compatible with the XML [Schema](../../) Definition Language (XSD) type of the attribute. |

## See Also

* Typedef [XmlValueGetter](../../xmlvaluegetter/)
* Class [XmlSchemaValidator](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)
