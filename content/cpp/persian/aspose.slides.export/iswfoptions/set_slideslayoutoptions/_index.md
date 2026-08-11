---
title: set_SlidesLayoutOptions()
second_title: مرجع API Aspose.Slides برای C++
description: حالت قرارگیری اسلایدها بر روی صفحه هنگام خروجی گرفتن از یک ارائه ISlidesLayoutOptions را تنظیم می‌کند. این ویژگی از اختصاص اشیاء از نوع Aspose.Slides.Export.HandoutLayoutingOptions پشتیبانی نمی‌کند.
type: docs
weight: 404
url: /fa/aspose.slides.export/iswfoptions/set_slideslayoutoptions/
---
## ISwfOptions::set_SlidesLayoutOptions(System::SharedPtr\<ISlidesLayoutOptions\>) متد

حالت قرارگیری اسلایدها روی صفحه هنگام خروجی گرفتن یک ارائه [ISlidesLayoutOptions](../../islideslayoutoptions/) را تنظیم می‌کند. این ویژگی از اختصاص شیءهایی از نوع **[Aspose.Slides.Export.HandoutLayoutingOptions](../../handoutlayoutingoptions/)** پشتیبانی نمی‌کند.

```cpp
virtual void Aspose::Slides::Export::ISwfOptions::set_SlidesLayoutOptions(System::SharedPtr<ISlidesLayoutOptions> value)=0
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
* کتابخانه [Aspose.Slides](../../../)