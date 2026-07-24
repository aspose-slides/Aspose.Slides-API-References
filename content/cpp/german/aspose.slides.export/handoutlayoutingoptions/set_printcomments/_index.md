---
title: set_PrintComments()
second_title: Aspose.Slides für C++ API Referenz
description: Gibt an, ob Kommentare auf Folien angezeigt werden sollen
type: docs
weight: 92
url: /de/aspose.slides.export/handoutlayoutingoptions/set_printcomments/
---
## HandoutLayoutingOptions::set_PrintComments(bool) Methode


Gibt an, ob Kommentare auf Folien angezeigt werden sollen

```cpp
void Aspose::Slides::Export::HandoutLayoutingOptions::set_PrintComments(bool value)
```

## Hinweise


Der Standardwert ist **false**. 

Beispiel: 
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

## Siehe auch

* Klasse [HandoutLayoutingOptions](../)
* Namensraum [Aspose::Slides::Export](../../)
* Bibliothek [Aspose.Slides](../../../)