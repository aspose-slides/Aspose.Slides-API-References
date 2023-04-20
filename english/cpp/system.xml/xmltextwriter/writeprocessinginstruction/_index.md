---
title: WriteProcessingInstruction()
second_title: Aspose.Slides for C++ API Reference
description: "Writes out a processing instruction with a space between the name and text as follows: <?name text?>."
type: docs
weight: 326
url: /cpp/system.xml/xmltextwriter/writeprocessinginstruction/
---
## XmlTextWriter::WriteProcessingInstruction(String, String) method


Writes out a processing instruction with a space between the name and text as follows: **<?name text?>**.

```cpp
void System::Xml::XmlTextWriter::WriteProcessingInstruction(String name, String text) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Name of the processing instruction. |
| text | [String](../../../system/string/) | [Text](../../../system.text/) to include in the processing instruction. |
## Remarks



This method is being used to create an XML declaration after [XmlTextWriter::WriteStartDocument](../writestartdocument/) has already been called. 
## See Also

* Class [String](../../../system/string/)
* Class [XmlTextWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)