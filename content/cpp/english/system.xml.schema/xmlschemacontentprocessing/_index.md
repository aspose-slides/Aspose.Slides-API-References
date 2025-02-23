---
title: XmlSchemaContentProcessing
second_title: Aspose.Slides for C++ API Reference
description: Provides information about the validation mode of any and anyAttribute element replacements.
type: docs
weight: 976
url: /system.xml.schema/xmlschemacontentprocessing/
---
## XmlSchemaContentProcessing enum


Provides information about the validation mode of **any** and **anyAttribute** element replacements.

```cpp
enum class XmlSchemaContentProcessing
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| None | 0 | Document items are not validated. |
| Skip | 1 | Document items must consist of well-formed XML and are not validated by the schema. |
| Lax | 2 | If the associated schema is found, the document items will be validated. No errors will be thrown otherwise. |
| Strict | 3 | The schema processor must find a schema associated with the indicated namespace to validate the document items. |

## See Also

* Namespace [System::Xml::Schema](../)
* Library [Aspose.Slides](../../)