---
title: get_SlidesLayoutOptions()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحصل على الوضع الذي تُوضع فيه الشرائح على الصفحة عند تصدير عرض تقديمي ISlidesLayoutOptions.
type: docs
weight: 209
url: /ar/aspose.slides.export/ihtmloptions/get_slideslayoutoptions/
---
## IHtmlOptions::get_SlidesLayoutOptions() طريقة

يحصل على الوضع الذي تُوضع فيه الشرائح على الصفحة عند تصدير عرض تقديمي [ISlidesLayoutOptions](../../islideslayoutoptions/).

```cpp
virtual System::SharedPtr<ISlidesLayoutOptions> Aspose::Slides::Export::IHtmlOptions::get_SlidesLayoutOptions()=0
```

## ملاحظات

مثال:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> handoutLayoutingOptions = System::MakeObject<HandoutLayoutingOptions>();
handoutLayoutingOptions->set_Handout(HandoutType::Handouts4Horizontal);

System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_SlidesLayoutOptions(handoutLayoutingOptions);

pres->Save(u"pres.html", SaveFormat::Html, options);
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [ISlidesLayoutOptions](../../islideslayoutoptions/)
* فئة [IHtmlOptions](../)
* مساحة اسم [Aspose::Slides::Export](../../)
* مكتبة [Aspose.Slides](../../../)