---
title: WriteCData()
second_title: Aspose.Slides for C++ API Reference
description: Writes out a ... block containing the specified text.
type: docs
weight: 300
url: /system.xml/xmltextwriter/writecdata/
---
## XmlTextWriter::WriteCData(String) method


Writes out a **...** block containing the specified text.

```cpp
void System::Xml::XmlTextWriter::WriteCData(String text) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| text | [String](../../../system/string/) | [Text](../../../system.text/) to place inside the CDATA block. |

### Exceptions

| Exception | Description |
| --- | --- |
| ArgumentException | The text would result in a non-well formed XML document. |
| InvalidOperationException | The [XmlTextWriter::get_WriteState](../get_writestate/) value is [WriteState::Closed](../../writestate/). |


## See Also

* Class [String](../../../system/string/)
* Class [XmlTextWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)