---
title: NewLineHandling
second_title: Aspose.Slides for C++ API Reference
description: Specifies how to handle line breaks.
type: docs
weight: 664
url: /cpp/system.xml/newlinehandling/
---
## NewLineHandling enum


Specifies how to handle line breaks.

```cpp
enum class NewLineHandling
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Replace | 0 | New line characters are replaced to match the character specified in the [XmlWriterSettings::set_NewLineChars](../xmlwritersettings/set_newlinechars/) value. |
| Entitize | 1 | New line characters are entitized. This setting preserves all characters when the output is read by a normalizing [XmlReader](../xmlreader/). |
| None | 2 | The new line characters are unchanged. The output is the same as the input. |

## See Also

* Namespace [System::Xml](../)
* Library [Aspose.Slides](../../)