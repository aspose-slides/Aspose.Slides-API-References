---
title: MarkdownImageSavingHandler
second_title: Aspose.Slides for C++ API Reference
description: Invoked for each non-SVG image (bitmap or metafile) during Markdown export.  Return true to use the specified link ,  or false to apply the default saving logic.
type: docs
weight: 300
url: /aspose.slides.export/markdownsaveoptions/markdownimagesavinghandler/
---
## MarkdownImageSavingHandler typedef


Invoked for each non-SVG image (bitmap or metafile) during Markdown export. 

 Return **true** to use the specified *link* , 

 or **false** to apply the default saving logic.

```cpp
using Aspose::Slides::Export::MarkdownSaveOptions::MarkdownImageSavingHandler =  System::MulticastDelegate<bool(System::SharedPtr<IImage>, ImageFormat, System::String&)>
```


## See Also

* Class [MarkdownSaveOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)