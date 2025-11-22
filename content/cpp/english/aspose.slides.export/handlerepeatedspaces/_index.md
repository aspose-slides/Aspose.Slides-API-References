---
title: HandleRepeatedSpaces
second_title: Aspose.Slides for C++ API Reference
description: Specifies how repeated regular space characters should be handled during Markdown export.
type: docs
weight: 924
url: /aspose.slides.export/handlerepeatedspaces/
---
## HandleRepeatedSpaces enum


Specifies how repeated regular space characters should be handled during Markdown export.

```cpp
enum class HandleRepeatedSpaces
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| None | 0 | All spaces are preserved as regular space characters without any changes. No transformation is applied, and multiple consecutive spaces are exported as-is. |
| AlternateSpacesToNbsp | 1 | Converts sequences of two or more consecutive regular spaces by alternating between regular space characters and non-breaking space entities (**&nbsp;**). The first space is always preserved as a regular space. |
| MultipleSpacesToNbsp | 2 | Converts sequences of two or more consecutive regular spaces by preserving the first space as a regular space character and replacing all subsequent spaces with non-breaking space entities (**&nbsp;**). |

## See Also

* Namespace [Aspose::Slides::Export](../)
* Library [Aspose.Slides](../../)