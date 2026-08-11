---
title: get_SlidesLayoutOptions()
second_title: مرجع API Aspose.Slides برای C++
description: حالت قرار گرفتن اسلایدها بر روی صفحه هنگام صادرات یک ارائه ISlidesLayoutOptions را دریافت می‌کند. این ویژگی از اختصاص اشیاء از نوع Aspose.Slides.Export.HandoutLayoutingOptions پشتیبانی نمی‌کند
type: docs
weight: 391
url: /fa/aspose.slides.export/iswfoptions/get_slideslayoutoptions/
---
## ISwfOptions::get_SlidesLayoutOptions() متد


حالت قرارگرفتن اسلایدها بر روی صفحه هنگام صادرات ارائه [ISlidesLayoutOptions](../../islideslayoutoptions/) را دریافت می‌کند. این ویژگی از اختصاص اشیاء از نوع **[Aspose.Slides.Export.HandoutLayoutingOptions](../../handoutlayoutingoptions/)** پشتیبانی نمی‌کند.

```cpp
virtual System::SharedPtr<ISlidesLayoutOptions> Aspose::Slides::Export::ISwfOptions::get_SlidesLayoutOptions()=0
```

## توضیحات


مثال:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_CommentsPosition(CommentsPositions::Right);

System::SharedPtr<SwfOptions> options = System::MakeObject<SwfOptions>();
options->set_SlidesLayoutOptions(slidesLayoutOptions);

pres->Save(u"pres.swf", SaveFormat::Swf, options);
```

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [ISlidesLayoutOptions](../../islideslayoutoptions/)
* کلاس [ISwfOptions](../)
* فضای‌نام [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)