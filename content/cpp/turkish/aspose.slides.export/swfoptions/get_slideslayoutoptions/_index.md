---
title: get_SlidesLayoutOptions()
second_title: Aspose.Slides for C++ API Referansı
description: Bir sunumu dışa aktarırken slaytların sayfada yerleştirildiği modu ISlidesLayoutOptions alır. Bu özellik, HandoutLayoutingOptions türündeki nesnelerin atanmasını desteklemez.
type: docs
weight: 391
url: /tr/aspose.slides.export/swfoptions/get_slideslayoutoptions/
---
## SwfOptions::get_SlidesLayoutOptions() yöntemi


Bir sunumu dışa aktarırken slaytların sayfada yerleştirildiği modu alır [ISlidesLayoutOptions](../../islideslayoutoptions/). Bu özellik, [HandoutLayoutingOptions](../../handoutlayoutingoptions/) türündeki nesnelerin atanmasını desteklemez.

```cpp
System::SharedPtr<ISlidesLayoutOptions> Aspose::Slides::Export::SwfOptions::get_SlidesLayoutOptions() override
```

## Açıklamalar


Örnek: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_CommentsPosition(CommentsPositions::Right);

System::SharedPtr<SwfOptions> options = System::MakeObject<SwfOptions>();
options->set_SlidesLayoutOptions(slidesLayoutOptions);

pres->Save(u"pres.swf", SaveFormat::Swf, options);
```

## Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [ISlidesLayoutOptions](../../islideslayoutoptions/)
* Sınıf [SwfOptions](../)
* Ad alanı [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)