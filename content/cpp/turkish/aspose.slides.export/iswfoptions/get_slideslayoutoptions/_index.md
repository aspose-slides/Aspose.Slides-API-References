---
title: get_SlidesLayoutOptions()
second_title: Aspose.Slides for C++ API Referansı
description: Bir sunumu dışa aktarırken slaytların sayfada yerleştirildiği modu ISlidesLayoutOptions alır. Bu özellik, Aspose.Slides.Export.HandoutLayoutingOptions türündeki nesnelerin atanmasını desteklemez
type: docs
weight: 391
url: /tr/aspose.slides.export/iswfoptions/get_slideslayoutoptions/
---
## ISwfOptions::get_SlidesLayoutOptions() metodu


Sunumu dışa aktarırken slaytların sayfada yerleştirildiği modu alır [ISlidesLayoutOptions](../../islideslayoutoptions/). Bu özellik, **[Aspose.Slides.Export.HandoutLayoutingOptions](../../handoutlayoutingoptions/)** türündeki nesnelerin atanmasını desteklemez

```cpp
virtual System::SharedPtr<ISlidesLayoutOptions> Aspose::Slides::Export::ISwfOptions::get_SlidesLayoutOptions()=0
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

## Ayrıca Bakınız

* Tip tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [ISlidesLayoutOptions](../../islideslayoutoptions/)
* Sınıf [ISwfOptions](../)
* Ad alanı [Aspose::Slides::Export](../../)
* Kütüphane [Aspose.Slides](../../../)