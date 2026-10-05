---
title: WriteCharEntity()
second_title: Aspose.Slides for C++ API Reference
description: Forces the generation of a character entity for the specified Unicode character value.
type: docs
weight: 352
url: /system.xml/xmltextwriter/writecharentity/
---
## XmlTextWriter::WriteCharEntity(char16_t) method


Forces the generation of a character entity for the specified Unicode character value.

```cpp
void System::Xml::XmlTextWriter::WriteCharEntity(char16_t ch) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| ch | char16_t | Unicode character for which to generate a character entity. |

### Exceptions

| Exception | Description |
| --- | --- |
| ArgumentException | The character is in the surrogate pair character range, **0xd800** - **0xdfff**; or the text would result in a non-well formed XML document. |
| InvalidOperationException | The [XmlTextWriter::get_WriteState](../get_writestate/) value is [WriteState::Closed](../../writestate/). |


## See Also

* Class [XmlTextWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)