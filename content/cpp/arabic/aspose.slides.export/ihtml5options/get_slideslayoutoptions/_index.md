---
title: get_SlidesLayoutOptions()
second_title: Aspose.Slides لـ C++ مرجع API
description: يحصل على الوضع الذي تُوضع فيه الشرائح على الصفحة عند تصدير عرض تقديمي ISlidesLayoutOptions.
type: docs
weight: 157
url: /ar/aspose.slides.export/ihtml5options/get_slideslayoutoptions/
---
## IHtml5Options::get_SlidesLayoutOptions() طريقة

يحصل على الوضع الذي توضع فيه الشرائح على الصفحة عند تصدير عرض تقديمي [ISlidesLayoutOptions](../../islideslayoutoptions/).

```cpp
virtual System::SharedPtr<ISlidesLayoutOptions> Aspose::Slides::Export::IHtml5Options::get_SlidesLayoutOptions()=0
```

## ملاحظات

مثال: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> slidesLayoutOptions = System::MakeObject<HandoutLayoutingOptions>();
slidesLayoutOptions->set_Handout(HandoutType::Handouts4Horizontal);

System::SharedPtr<Html5Options> options = System::MakeObject<Html5Options>();
options->set_SlidesLayoutOptions(slidesLayoutOptions);

pres->Save(u"pres.html", SaveFormat::Html5, options);
```

## أنظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [ISlidesLayoutOptions](../../islideslayoutoptions/)
* فئة [IHtml5Options](../)
* نطاق [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)