---
title: get_Handout()
second_title: Aspose.Slides C++ API referencia
description: Megadja, hogy hány diát és milyen sorrendben helyeznek el az oldalon HandoutType.
type: docs
weight: 1
url: /hu/aspose.slides.export/handoutlayoutingoptions/get_handout/
---
## HandoutLayoutingOptions::get_Handout() const metódus
Megadja, hogy hány dia és milyen sorrendben lesz elhelyezve az oldalon [HandoutType](../../handouttype/).
```cpp
HandoutType Aspose::Slides::Export::HandoutLayoutingOptions::get_Handout() const
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

* Enumeráció [HandoutType](../../handouttype/)
* Osztály [HandoutLayoutingOptions](../)
* Névtér [Aspose::Slides::Export](../../)
* Könyvtár [Aspose.Slides](../../../)