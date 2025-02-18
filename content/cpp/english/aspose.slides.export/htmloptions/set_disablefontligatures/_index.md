---
title: set_DisableFontLigatures()
second_title: Aspose.Slides for C++ API Reference
description: Sets a value indicating whether text is rendered without using ligatures. When set to true, ligatures will be disabled in the rendered output. By default, this property is set to false.
type: docs
weight: 105
url: /aspose.slides.export/htmloptions/set_disablefontligatures/
---
## HtmlOptions::set_DisableFontLigatures(bool) method


Sets a value indicating whether text is rendered without using ligatures. When set to **true**, ligatures will be disabled in the rendered output. By default, this property is set to **false**.

```cpp
void Aspose::Slides::Export::HtmlOptions::set_DisableFontLigatures(bool value) override
```

## Remarks


Example: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_DisableFontLigatures(true); // Disable ligatures in text rendering

pres->Save(outputSlidePath, SaveFormat::Html, options);
```

## See Also

* Class [HtmlOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)