---
title: get_EmbedImages()
second_title: Aspose.Slides برای مرجع API C++
description: گزینهٔ جاسازی تصاویر را برمی‌گرداند. خواندنی bool.
type: docs
weight: 53
url: /fa/aspose.slides.export/ihtml5options/get_embedimages/
---
## IHtml5Options::get_EmbedImages() متد

گزینهٔ جاسازی تصاویر را برمی‌گرداند. قابل خواندن **bool**.

```cpp
virtual bool Aspose::Slides::Export::IHtml5Options::get_EmbedImages()=0
```

## ملاحظات

مثال: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<Html5Options> html5Options = System::MakeObject<Html5Options>();
html5Options->set_EmbedImages(false);
pres->Save(u"demo-linked-images.html", SaveFormat::Html5, html5Options);
```

## نکات مرتبط

* کلاس [IHtml5Options](../)
* فضای‌نام [Aspose::Slides::Export](../../)
* کتابخانه [Aspose.Slides](../../../)