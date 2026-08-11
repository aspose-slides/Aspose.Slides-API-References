---
title: set_SlidesLayoutOptions()
second_title: Aspose.Slides لمرجع API الخاص بـ C++
description: يحدد الوضع الذي تُوضع فيه الشرائح على الصفحة عند تصدير عرض تقديمي ISlidesLayoutOptions.
type: docs
weight: 378
url: /ar/aspose.slides.export/ipdfoptions/set_slideslayoutoptions/
---
## IPdfOptions::set_SlidesLayoutOptions(System::SharedPtr\<ISlidesLayoutOptions\>) الطريقة


يحدد الوضع الذي تُوضع فيه الشرائح على الصفحة عند تصدير عرض تقديمي [ISlidesLayoutOptions](../../islideslayoutoptions/).

```cpp
virtual void Aspose::Slides::Export::IPdfOptions::set_SlidesLayoutOptions(System::SharedPtr<ISlidesLayoutOptions> value)=0
```

## ملاحظات


مثال:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> handoutLayoutingOptions = System::MakeObject<HandoutLayoutingOptions>();
handoutLayoutingOptions->set_Handout(HandoutType::Handouts4Horizontal);

System::SharedPtr<PdfOptions> options = System::MakeObject<PdfOptions>();
options->set_SlidesLayoutOptions(handoutLayoutingOptions);

pres->Save(u"pres.pdf", SaveFormat::Pdf, options);
```

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [ISlidesLayoutOptions](../../islideslayoutoptions/)
* فئة [IPdfOptions](../)
* مساحة الأسماء [Aspose::Slides::Export](../../)
* مكتبة [Aspose.Slides](../../../)