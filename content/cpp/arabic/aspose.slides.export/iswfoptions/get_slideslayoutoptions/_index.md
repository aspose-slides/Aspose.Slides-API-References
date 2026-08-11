---
title: get_SlidesLayoutOptions()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحصل على الوضع الذي تُوضع فيه الشرائح على الصفحة عند تصدير عرض تقديمي ISlidesLayoutOptions. لا تدعم هذه الخاصية تعيين كائنات من النوع Aspose.Slides.Export.HandoutLayoutingOptions
type: docs
weight: 391
url: /ar/aspose.slides.export/iswfoptions/get_slideslayoutoptions/
---
## ISwfOptions::get_SlidesLayoutOptions() الطريقة

يحصل على الوضع الذي تُوضع فيه الشرائح على الصفحة عند تصدير عرض تقديمي [ISlidesLayoutOptions](../../islideslayoutoptions/). لا تدعم هذه الخاصية تعيين كائنات من النوع **[Aspose.Slides.Export.HandoutLayoutingOptions](../../handoutlayoutingoptions/)**

```cpp
virtual System::SharedPtr<ISlidesLayoutOptions> Aspose::Slides::Export::ISwfOptions::get_SlidesLayoutOptions()=0
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

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [ISlidesLayoutOptions](../../islideslayoutoptions/)
* فئة [ISwfOptions](../)
* النطاق [Aspose::Slides::Export](../../)
* المكتبة [Aspose.Slides](../../../)