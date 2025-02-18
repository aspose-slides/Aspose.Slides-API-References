---
title: get_DisableFontLigatures()
second_title: Aspose.Slides for C++ API Reference
description: Gets a value indicating whether text is rendered without using ligatures. When set to true, ligatures will be disabled in the rendered output. By default, this property is set to false.
type: docs
weight: 40
url: /aspose.slides.export/renderingoptions/get_disablefontligatures/
---
## RenderingOptions::get_DisableFontLigatures() method


Gets a value indicating whether text is rendered without using ligatures. When set to **true**, ligatures will be disabled in the rendered output. By default, this property is set to **false**.

```cpp
bool Aspose::Slides::Export::RenderingOptions::get_DisableFontLigatures() override
```

## Remarks


Example: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_DisableFontLigatures(true); // Disable ligatures in text rendering

System::ArrayPtr<System::SharedPtr<IImage>> renderedSlides = pres->GetImages(options);
for (int32_t index = 0; index < renderedSlides->get_Length(); index++)
{
    auto slideImage = renderedSlides[index];
    slideImage->Save(System::String::Format(u"slide-{0}.png", index));
}
```

## See Also

* Class [RenderingOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)