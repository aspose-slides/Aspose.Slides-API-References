---
title: WriteSurrogateCharEntity()
second_title: Aspose.Slides for C++ API Reference
description: When overridden in a derived class, generates and writes the surrogate character entity for the surrogate character pair.
type: docs
weight: 261
url: /system.xml/xmlwriter/writesurrogatecharentity/
---
## XmlWriter::WriteSurrogateCharEntity(char16_t, char16_t) method


When overridden in a derived class, generates and writes the surrogate character entity for the surrogate character pair.

```cpp
virtual void System::Xml::XmlWriter::WriteSurrogateCharEntity(char16_t lowChar, char16_t highChar)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| lowChar | char16_t | The low surrogate. This must be a value between 0xDC00 and 0xDFFF. |
| highChar | char16_t | The high surrogate. This must be a value between 0xD800 and 0xDBFF. |

## See Also

* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)