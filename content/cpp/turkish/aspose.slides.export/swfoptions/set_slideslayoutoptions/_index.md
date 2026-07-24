---
title: set_SlidesLayoutOptions()
second_title: Aspose.Slides C++ API Referansı
description: Bir sunumu dışa aktarırken slaytların sayfada yerleştirildiği modu ayarlar ISlidesLayoutOptions. Bu özellik HandoutLayoutingOptions türündeki nesnelerin atanmasını desteklemez.
type: docs
weight: 404
url: /tr/aspose.slides.export/swfoptions/set_slideslayoutoptions/
---
## SwfOptions::set_SlidesLayoutOptions(System::SharedPtr\<ISlidesLayoutOptions\>) yöntemi

Bir sunumu dışa aktarırken slaytların sayfada yerleştirildiği modu ayarlar [ISlidesLayoutOptions](../../islideslayoutoptions/). Bu özellik [HandoutLayoutingOptions](../../handoutlayoutingoptions/) tipinde nesnelerin atanmasını desteklemez

```cpp
void Aspose::Slides::Export::SwfOptions::set_SlidesLayoutOptions(System::SharedPtr<ISlidesLayoutOptions> value) override
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
* Kütüphane [Aspose.Slides](../../../)