---
title: get_SlidesLayoutOptions()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يجلب الوضع الذي توضع به الشرائح على الصفحة عند تصدير عرض تقديمي ISlidesLayoutOptions. هذه الخاصية لا تدعم تعيين كائنات من النوع HandoutLayoutingOptions
type: docs
weight: 391
url: /ar/aspose.slides.export/swfoptions/get_slideslayoutoptions/
---
## SwfOptions::get_SlidesLayoutOptions() طريقة


يحصل على الوضع الذي يتم فيه وضع الشرائح على الصفحة عند تصدير عرض تقديمي [ISlidesLayoutOptions](../../islideslayoutoptions/). هذه الخاصية لا تدعم تعيين كائنات من النوع [HandoutLayoutingOptions](../../handoutlayoutingoptions/)

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

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [ISlidesLayoutOptions](../../islideslayoutoptions/)
* فئة [SwfOptions](../)
* نطاق [Aspose::Slides::Export](../../)
* مكتبة [Aspose.Slides](../../../)