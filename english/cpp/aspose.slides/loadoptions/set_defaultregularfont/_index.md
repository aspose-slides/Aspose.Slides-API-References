---
title: set_DefaultRegularFont()
second_title: Aspose.Slides for C++ API Reference
description: "Sets Regular font used in case source font is not found. Write System::String."
type: docs
weight: 40
url: /cpp/aspose.slides/loadoptions/set_defaultregularfont/
---
## LoadOptions::set_DefaultRegularFont(System::String) method


Sets Regular font used in case source font is not found. Write [System::String](../../../system/string/).

```cpp
void Aspose::Slides::LoadOptions::set_DefaultRegularFont(System::String value) override
```

## Remarks


The following example shows how to set default fonts for rendering PowerPoint [Presentation](../../presentation/). 
```cpp
// Use load options to define the default regular and asian fonts
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>(LoadFormat::Auto);
loadOptions->set_DefaultRegularFont(u"Wingdings");
loadOptions->set_DefaultAsianFont(u"Wingdings");

// Load the presentation
auto pptx = System::MakeObject<Presentation>(u"DefaultFonts.pptx", loadOptions);
// Generate slide thumbnail
auto slide = pptx->get_Slides()->idx_get(0);
slide->GetThumbnail(1.0f, 1.0f)->Save(u"output_out.png", System::Drawing::Imaging::ImageFormat::get_Png());

// Generate PDF
pptx->Save(u"output_out.pdf", SaveFormat::Pdf);
// Generate XPS
pptx->Save(u"output_out.xps", SaveFormat::Xps);
```

## See Also

* Class [String](../../../system/string/)
* Class [LoadOptions](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)