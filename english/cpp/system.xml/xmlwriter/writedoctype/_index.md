---
title: WriteDocType()
second_title: Aspose.Slides for C++ API Reference
description: When overridden in a derived class, writes the DOCTYPE declaration with the specified name and optional attributes.
type: docs
weight: 79
url: /cpp/system.xml/xmlwriter/writedoctype/
---
## XmlWriter::WriteDocType(const String\&, const String\&, const String\&, const String\&) method


When overridden in a derived class, writes the DOCTYPE declaration with the specified name and optional attributes.

```cpp
virtual void System::Xml::XmlWriter::WriteDocType(const String &name, const String &pubid, const String &sysid, const String &subset)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | The name of the DOCTYPE. This must be non-empty. |
| pubid | const [String](../../../system/string/)\& | If non-null it also writes PUBLIC \"pubid\" \"sysid\" where **pubid** and **sysid** are replaced with the value of the given arguments. |
| sysid | const [String](../../../system/string/)\& | If **pubid** is **nullptr** and **sysid** is non-null it writes SYSTEM \"sysid\" where **sysid** is replaced with the value of this argument. |
| subset | const [String](../../../system/string/)\& | If non-null it writes [subset] where subset is replaced with the value of this argument. |

## See Also

* Class [String](../../../system/string/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)