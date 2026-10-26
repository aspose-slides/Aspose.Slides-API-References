---
title: set_Handout()
second_title: Aspose.Slides for C++ API-referenciája
description: Megadja, hogy hány dia és milyen sorrendben kerül elhelyezésre az oldalon a HandoutType.
type: docs
weight: 14
url: /hu/aspose.slides.export/handoutlayoutingoptions/set_handout/
---
## HandoutLayoutingOptions::set_Handout(HandoutType) metódus

Megadja, hogy hány dia és milyen sorrendben kerül elhelyezésre az oldalon [HandoutType](../../handouttype/).

```cpp
void Aspose::Slides::Export::HandoutLayoutingOptions::set_Handout(HandoutType value)
```

## Megjegyzések

Az alapértelmezett érték **[HandoutType::Handouts6Horizontal](../../handouttype/)**. 

Példa: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> handoutLayoutingOptions = System::MakeObject<HandoutLayoutingOptions>();
handoutLayoutingOptions->set_Handout(HandoutType::Handouts4Horizontal);

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_SlidesLayoutOptions(handoutLayoutingOptions);

System::Drawing::Size size(1920, 1080);
pres->get_Slide(0)->GetThumbnail(options, size)->Save(u"pres-handout.png");
```

## Lásd még

* enum [HandoutType](../../handouttype/)
* osztály [HandoutLayoutingOptions](../)
* névtér [Aspose::Slides::Export](../../)
* könyvtár [Aspose.Slides](../../../)