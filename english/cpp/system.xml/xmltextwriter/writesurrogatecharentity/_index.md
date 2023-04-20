---
title: WriteSurrogateCharEntity()
second_title: Aspose.Slides for C++ API Reference
description: Generates and writes the surrogate character entity for the surrogate character pair.
type: docs
weight: 391
url: /cpp/system.xml/xmltextwriter/writesurrogatecharentity/
---
## XmlTextWriter::WriteSurrogateCharEntity(char16_t, char16_t) method


Generates and writes the surrogate character entity for the surrogate character pair.

```cpp
void System::Xml::XmlTextWriter::WriteSurrogateCharEntity(char16_t lowChar, char16_t highChar) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| lowChar | char16_t | The low surrogate. This must be a value between **0xDC00** and **0xDFFF**. |
| highChar | char16_t | The high surrogate. This must be a value between **0xD800** and **0xDBFF**. |

## See Also

* Class [XmlTextWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)