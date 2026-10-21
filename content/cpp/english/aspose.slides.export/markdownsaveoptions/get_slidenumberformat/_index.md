---
title: get_SlideNumberFormat()
second_title: Aspose.Slides for C++ API Reference
description: "Gets the format string used for slide number headers in Markdown output. The format must include the \"{0}\" placeholder, which will be replaced with the slide index during export. Example: \"# Slide {0}\" will produce \"# Slide 1\", \"# Slide 2\", etc."
type: docs
weight: 209
url: /aspose.slides.export/markdownsaveoptions/get_slidenumberformat/
---
## MarkdownSaveOptions::get_SlideNumberFormat() method


Gets the format string used for slide number headers in Markdown output. The format must include the "{0}" placeholder, which will be replaced with the slide index during export. Example: "# Slide {0}" will produce "# Slide 1", "# Slide 2", etc.

```cpp
System::String Aspose::Slides::Export::MarkdownSaveOptions::get_SlideNumberFormat()
```


### Exceptions

| Exception | Description |
| --- | --- |
| [System::ArgumentNullException](../../../system/argumentnullexception/) | Thrown if the provided value is null or empty. |
| [System::ArgumentException](../../../system/argumentexception/) | Thrown if the format string does not contain the "{0}" placeholder. |


## See Also

* Class [String](../../../system/string/)
* Class [MarkdownSaveOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)