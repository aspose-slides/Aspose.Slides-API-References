---
title: set_SlidesLayoutOptions()
second_title: مرجع Aspose.Slides لواجهة برمجة تطبيقات C++
description: يضبط الوضع الذي توضع فيه الشرائح على الصفحة عند تصدير عرض تقديمي ISlidesLayoutOptions. هذه الخاصية لا تدعم تعيين كائنات من النوع HandoutLayoutingOptions
type: docs
weight: 404
url: /ar/aspose.slides.export/swfoptions/set_slideslayoutoptions/
---
## SwfOptions::set_SlidesLayoutOptions(System::SharedPtr\<ISlidesLayoutOptions\>) طريقة

يضبط الوضع الذي تُوضع فيه الشرائح على الصفحة عند تصدير عرض تقديمي [ISlidesLayoutOptions](../../islideslayoutoptions/). هذه الخاصية لا تدعم تعيين كائنات من النوع [HandoutLayoutingOptions](../../handoutlayoutingoptions/)

```cpp
void Aspose::Slides::Export::SwfOptions::set_SlidesLayoutOptions(System::SharedPtr<ISlidesLayoutOptions> value) override
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
* فئة [SwfOptions](../)
* مساحة الاسم [Aspose::Slides::Export](../../)
* مكتبة [Aspose.Slides](../../../)