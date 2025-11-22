---
title: MarkdownSvgImageSavingHandler
second_title: Aspose.Slides for C++ API Reference
description: Invoked for each SVG image during Markdown export.  Return true to use the specified link ,  or false to apply the default saving logic.
type: docs
weight: 313
url: /aspose.slides.export/markdownsaveoptions/markdownsvgimagesavinghandler/
---
## MarkdownSvgImageSavingHandler typedef


Invoked for each SVG image during Markdown export. 

 Return **true** to use the specified *link* , 

 or **false** to apply the default saving logic.

```cpp
using Aspose::Slides::Export::MarkdownSaveOptions::MarkdownSvgImageSavingHandler =  System::MulticastDelegate<bool(System::SharedPtr<ISvgImage>, System::String&)>
```


## See Also

* Class [MarkdownSaveOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)