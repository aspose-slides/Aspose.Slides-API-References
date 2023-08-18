---
title: WriteProcessingInstruction()
second_title: Aspose.Slides for C++ API Reference
description: "When overridden in a derived class, writes out a processing instruction with a space between the name and text as follows: <?name text?>."
type: docs
weight: 196
url: /system.xml/xmlwriter/writeprocessinginstruction/
---
## XmlWriter::WriteProcessingInstruction(String, String) method


When overridden in a derived class, writes out a processing instruction with a space between the name and text as follows: **<?name text?>**.

```cpp
virtual void System::Xml::XmlWriter::WriteProcessingInstruction(String name, String text)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | The name of the processing instruction. |
| text | [String](../../../system/string/) | The text to include in the processing instruction. |
## Remarks



This method is being used to create an XML declaration after [XmlWriter::WriteStartDocument](../writestartdocument/) has already been called. 
## See Also

* Class [String](../../../system/string/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)