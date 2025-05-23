---
title: set_HandleRepeatedSpaces()
second_title: Aspose.Slides for C++ API Reference
description: Specifies how repeated regular space characters should be handled during Markdown export.
type: docs
weight: 248
url: /aspose.slides.export/markdownsaveoptions/set_handlerepeatedspaces/
---
## MarkdownSaveOptions::set_HandleRepeatedSpaces(Aspose::Slides::Export::HandleRepeatedSpaces) method


Specifies how repeated regular space characters should be handled during Markdown export.

```cpp
void Aspose::Slides::Export::MarkdownSaveOptions::set_HandleRepeatedSpaces(Aspose::Slides::Export::HandleRepeatedSpaces value)
```

## Remarks


This property defines whether consecutive spaces are:* preserved as regular space characters,
* alternated between regular spaces and non-breaking space entities (**&nbsp;**),
* or fully replaced (after the first) with **&nbsp;** to preserve visual alignment in Markdown output.



The default value is [HandleRepeatedSpaces::AlternateSpacesToNbsp](../../handlerepeatedspaces/). 
## See Also

* Enum [HandleRepeatedSpaces](../../handlerepeatedspaces/)
* Class [MarkdownSaveOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)