---
title: set_PrintSlideNumbers()
second_title: Aspose.Slides C++ API referenciája
description: Megadja, hogy a megjelenített diaszámok nyomtatása megtörténjen-e.
type: docs
weight: 40
url: /hu/aspose.slides.export/handoutlayoutingoptions/set_printslidenumbers/
---
## HandoutLayoutingOptions::set_PrintSlideNumbers(bool) metódus


Megadja, hogy a megjelenített diaszámok nyomtatása megtörténjen-e.

```cpp
void Aspose::Slides::Export::HandoutLayoutingOptions::set_PrintSlideNumbers(bool value)
```

## Megjegyzések


Az alapértelmezett érték **true**. 

Példa: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> handoutLayoutingOptions = System::MakeObject<HandoutLayoutingOptions>();
handoutLayoutingOptions->set_Handout(HandoutType::Handouts4Horizontal);
handoutLayoutingOptions->set_PrintSlideNumbers(false);

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_SlidesLayoutOptions(handoutLayoutingOptions);

System::Drawing::Size size(1920, 1080);
pres->get_Slide(0)->GetThumbnail(options, size)->Save(u"pres-handout.png");
```

## Lásd még

* Osztály [HandoutLayoutingOptions](../)
* Névtere [Aspose::Slides::Export](../../)
* Könyvtár [Aspose.Slides](../../../)