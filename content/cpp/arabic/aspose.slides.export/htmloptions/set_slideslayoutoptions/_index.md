---
title: set_SlidesLayoutOptions()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يضبط الوضع الذي تُوضع فيه الشرائح على الصفحة عند تصدير عرض تقديمي ISlidesLayoutOptions.
type: docs
weight: 14
url: /ar/aspose.slides.export/htmloptions/set_slideslayoutoptions/
---
## HtmlOptions::set_SlidesLayoutOptions(System::SharedPtr\<ISlidesLayoutOptions\>) طريقة

يضبط الوضع الذي تُوضع فيه الشرائح على الصفحة عند تصدير عرض تقديمي [ISlidesLayoutOptions](../../islideslayoutoptions/).

```cpp
void Aspose::Slides::Export::HtmlOptions::set_SlidesLayoutOptions(System::SharedPtr<ISlidesLayoutOptions> value) override
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
* فئة [HtmlOptions](../)
* مساحة اسم [Aspose::Slides::Export](../../)
* مكتبة [Aspose.Slides](../../../)