---
title: set_DisableFontLigatures()
second_title: Aspose.Slides for C++ API Reference
description: Sets a value indicating whether text is rendered without using ligatures. When set to true, ligatures will be disabled in the rendered output. By default, this property is set to false.
type: docs
weight: 339
url: /aspose.slides.export/svgoptions/set_disablefontligatures/
---
## SVGOptions::set_DisableFontLigatures(bool) method


Sets a value indicating whether text is rendered without using ligatures. When set to **true**, ligatures will be disabled in the rendered output. By default, this property is set to **false**.

```cpp
void Aspose::Slides::Export::SVGOptions::set_DisableFontLigatures(bool value) override
```

## Remarks


Example: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<SVGOptions> options = System::MakeObject<SVGOptions>();
options->set_DisableFontLigatures(true); // Disable ligatures in text rendering

System::SharedPtr<System::IO::FileStream> fileStream = System::MakeObject<System::IO::FileStream>(u"slide-0.svg", System::IO::FileMode::Create, System::IO::FileAccess::Write);
pres->get_Slide(0)->WriteAsSvg(fileStream);
```

## See Also

* Class [SVGOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)