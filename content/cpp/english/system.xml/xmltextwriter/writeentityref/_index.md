---
title: WriteEntityRef()
second_title: Aspose.Slides for C++ API Reference
description: Writes out an entity reference as &name;.
type: docs
weight: 339
url: /system.xml/xmltextwriter/writeentityref/
---
## XmlTextWriter::WriteEntityRef(const String&) method


Writes out an entity reference as **&name**;.

```cpp
void System::Xml::XmlTextWriter::WriteEntityRef(const String &name) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | const [String](../../../system/string/)& | Name of the entity reference. |

### Exceptions

| Exception | Description |
| --- | --- |
| ArgumentException | The text would result in a non-well formed XML document or **name** is either **nullptr** or [String::Empty](../../../system/string/empty/). |


## See Also

* Class [String](../../../system/string/)
* Class [XmlTextWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)