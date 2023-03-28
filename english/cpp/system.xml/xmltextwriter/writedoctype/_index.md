---
title: WriteDocType()
second_title: Aspose.Slides for C++ API Reference
description: Writes the DOCTYPE declaration with the specified name and optional attributes.
type: docs
weight: 222
url: /cpp/system.xml/xmltextwriter/writedoctype/
---
## XmlTextWriter::WriteDocType(const [String](../../../system/string/)\&, const [String](../../../system/string/)\&, const [String](../../../system/string/)\&, const [String](../../../system/string/)\&) method


Writes the DOCTYPE declaration with the specified name and optional attributes.

```cpp
void System::Xml::XmlTextWriter::WriteDocType(const String &name, const String &pubid, const String &sysid, const String &subset) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | The name of the DOCTYPE. This must be non-empty. |
| pubid | const [String](../../../system/string/)\& | If non-null it also writes PUBLIC \"pubid\" \"sysid\" where **pubid** and **sysid** are replaced with the value of the given arguments. |
| sysid | const [String](../../../system/string/)\& | If **pubid** is null and **sysid** is non-null it writes SYSTEM \"sysid\" where **sysid** is replaced with the value of this argument. |
| subset | const [String](../../../system/string/)\& | If non-null it writes [subset] where subset is replaced with the value of this argument. |

## See Also

* Class [String](../../../system/string/)
* Class [XmlTextWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
