---
title: set_EmbedImages()
second_title: Aspose.Slides برای C++ مرجع API
description: گزینهٔ جاسازی تصاویر را تنظیم می‌کند. مقدار bool را بنویسید.
type: docs
weight: 66
url: /fa/aspose.slides.export/ihtml5options/set_embedimages/
---
## IHtml5Options::set_EmbedImages(bool) متد

گزینه‌ی جاسازی تصاویر را تعیین می‌کند. مقدار **bool** را بنویسید.

```cpp
virtual void Aspose::Slides::Export::IHtml5Options::set_EmbedImages(bool value)=0
```

## توضیحات

مثال:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<Html5Options> html5Options = System::MakeObject<Html5Options>();
html5Options->set_EmbedImages(false);
pres->Save(u"demo-linked-images.html", SaveFormat::Html5, html5Options);
```

## موارد مرتبط

* کلاس [IHtml5Options](../)
* فضای نام [Aspose::Slides::Export](../../)
* کتابخانه [Aspose.Slides](../../../)