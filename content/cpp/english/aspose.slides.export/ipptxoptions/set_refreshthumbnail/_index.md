---
title: set_RefreshThumbnail()
second_title: Aspose.Slides for C++ API Reference
description: Specifies whether the presentation thumbnail will be refreshed. Write bool. Default value is true.
type: docs
weight: 66
url: /aspose.slides.export/ipptxoptions/set_refreshthumbnail/
---
## IPptxOptions::set_RefreshThumbnail(bool) method


Specifies whether the presentation thumbnail will be refreshed. Write **bool**. Default value is **true**.

```cpp
virtual void Aspose::Slides::Export::IPptxOptions::set_RefreshThumbnail(bool value)=0
```

## Remarks


When the option value is **true**, the new thumbnail will be generated.

When the option value is **false**, the current thumbnail will be saved as is.

Example: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_RefreshThumbnail(false);
pres->Save(u"result_with_old_thumbnail.pptx", SaveFormat::Pptx, pptxOptions);
```

## See Also

* Class [IPptxOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)