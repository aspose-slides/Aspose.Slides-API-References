---
title: get_ParagraphFormat()
second_title: Aspose.Slides for C++ API Reference
description: Returns the formatting object for this paragraph. Read-only IParagraphFormat.
type: docs
weight: 14
url: /cpp/aspose.slides/paragraph/get_paragraphformat/
---
## Paragraph::get_ParagraphFormat() method


Returns the formatting object for this paragraph. Read-only [IParagraphFormat](../../iparagraphformat/).

```cpp
System::SharedPtr<IParagraphFormat> Aspose::Slides::Paragraph::get_ParagraphFormat() override
```

## Remarks


The formatting object contains the formatting parameters defined for the current paragraph only, inherited data is not applied.

In order to get the effective values including inherited ones use the [ParagraphFormat::GetEffective](../../paragraphformat/geteffective/) method.
## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IParagraphFormat](../../iparagraphformat/)
* Class [Paragraph](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
