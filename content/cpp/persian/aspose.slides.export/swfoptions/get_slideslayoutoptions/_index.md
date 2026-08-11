---
title: get_SlidesLayoutOptions()
second_title: Aspose.Slides برای مرجع API C++
description: حالت قرارگیری اسلایدها بر روی صفحه هنگام صادر کردن یک ارائه ISlidesLayoutOptions را دریافت می‌کند. این ویژگی از اختصاص اشیاء از نوع HandoutLayoutingOptions پشتیبانی نمی‌کند
type: docs
weight: 391
url: /fa/aspose.slides.export/swfoptions/get_slideslayoutoptions/
---
## SwfOptions::get_SlidesLayoutOptions() متد

حالت قرارگیری اسلایدها بر روی صفحه هنگام صادر کردن ارائه [ISlidesLayoutOptions](../../islideslayoutoptions/) را دریافت می‌کند. این ویژگی از اختصاص اشیاء از نوع [HandoutLayoutingOptions](../../handoutlayoutingoptions/) پشتیبانی نمی‌کند.

```cpp
System::SharedPtr<ISlidesLayoutOptions> Aspose::Slides::Export::SwfOptions::get_SlidesLayoutOptions() override
```

## ملاحظات

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
* فضای‌نام [Aspose::Slides::Export](../../)
* کتابخانه [Aspose.Slides](../../../)