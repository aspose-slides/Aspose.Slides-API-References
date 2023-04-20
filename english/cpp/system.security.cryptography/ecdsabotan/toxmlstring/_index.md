---
title: ToXmlString()
second_title: Aspose.Slides for C++ API Reference
description: Exports all parameters in XML format. Not implemented.
type: docs
weight: 157
url: /cpp/system.security.cryptography/ecdsabotan/toxmlstring/
---
## ECDsaBotan::ToXmlString(bool) method


Exports all parameters in XML format. Not implemented.

```cpp
String System::Security::Cryptography::ECDsaBotan::ToXmlString(bool include_private_parameters) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| include_private_parameters | **bool** | True to export both private and public parameters, false to export public parameters only. |

### Return Value

XML-encoded parameters.

## ECDsaBotan::ToXmlString(ECKeyXmlFormat) method


Exports all parameters in XML format.

```cpp
String System::Security::Cryptography::ECDsaBotan::ToXmlString(ECKeyXmlFormat format)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| format | [ECKeyXmlFormat](../../eckeyxmlformat/) | Format of the result XML string. |

### Return Value

XML-encoded parameters.

## See Also

* Enum [ECKeyXmlFormat](../../eckeyxmlformat/)
* Class [String](../../../system/string/)
* Class [ECDsaBotan](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)