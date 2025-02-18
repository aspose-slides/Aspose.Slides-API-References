---
title: get_DisableFontLigatures()
second_title: Aspose.Slides for C++ API Reference
description: Gets a value indicating whether text is rendered without using ligatures. When set to true, ligatures will be disabled in the rendered output. By default, this property is set to false.
type: docs
weight: 326
url: /aspose.slides.export/isvgoptions/get_disablefontligatures/
---
## ISVGOptions::get_DisableFontLigatures() method


Gets a value indicating whether text is rendered without using ligatures. When set to **true**, ligatures will be disabled in the rendered output. By default, this property is set to **false**.

```cpp
virtual bool Aspose::Slides::Export::ISVGOptions::get_DisableFontLigatures()=0
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

* Class [ISVGOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)