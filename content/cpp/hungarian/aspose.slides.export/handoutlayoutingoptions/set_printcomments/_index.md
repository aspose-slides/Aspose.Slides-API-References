---
title: set_PrintComments()
second_title: Aspose.Slides C++ API referencia
description: Megadja, hogy a diákon megjelenjenek-e a megjegyzések
type: docs
weight: 92
url: /hu/aspose.slides.export/handoutlayoutingoptions/set_printcomments/
---
## HandoutLayoutingOptions::set_PrintComments(bool) metódus


Megadja, hogy a diákon megjelenjenek-e a megjegyzések

```cpp
void Aspose::Slides::Export::HandoutLayoutingOptions::set_PrintComments(bool value)
```

## Megjegyzés


Az alapértelmezett érték **false**. 

Példa: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> handoutLayoutingOptions = System::MakeObject<HandoutLayoutingOptions>();
handoutLayoutingOptions->set_Handout(HandoutType::Handouts4Horizontal);
handoutLayoutingOptions->set_PrintComments(false);

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_SlidesLayoutOptions(handoutLayoutingOptions);

System::Drawing::Size size(1920, 1080);
pres->get_Slide(0)->GetThumbnail(options, size)->Save(u"pres-handout.png");
```

## Lásd még

* Osztály [HandoutLayoutingOptions](../)
* Névtér [Aspose::Slides::Export](../../)
* Könyvtár [Aspose.Slides](../../../)