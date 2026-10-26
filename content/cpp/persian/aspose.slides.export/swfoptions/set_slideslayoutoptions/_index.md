---
title: set_SlidesLayoutOptions()
second_title: مرجع API Aspose.Slides برای C++
description: حالت قرار گرفتن اسلایدها بر روی صفحه هنگام استخراج یک ارائه ISlidesLayoutOptions تعیین می‌کند. این ویژگی از اختصاص اشیاء از نوع HandoutLayoutingOptions پشتیبانی نمی‌کند
type: docs
weight: 404
url: /fa/aspose.slides.export/swfoptions/set_slideslayoutoptions/
---
## SwfOptions::set_SlidesLayoutOptions(System::SharedPtr\<ISlidesLayoutOptions\>) متد

حالت قرار گرفتن اسلایدها بر روی صفحه هنگام استخراج ارائه را تنظیم می‌کند [ISlidesLayoutOptions](../../islideslayoutoptions/). این ویژگی از اختصاص اشیاء از نوع [HandoutLayoutingOptions](../../handoutlayoutingoptions/) پشتیبانی نمی‌کند.

```cpp
void Aspose::Slides::Export::SwfOptions::set_SlidesLayoutOptions(System::SharedPtr<ISlidesLayoutOptions> value) override
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

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [ISlidesLayoutOptions](../../islideslayoutoptions/)
* کلاس [SwfOptions](../)
* فضای نام [Aspose::Slides::Export](../../)
* کتابخانه [Aspose.Slides](../../../)