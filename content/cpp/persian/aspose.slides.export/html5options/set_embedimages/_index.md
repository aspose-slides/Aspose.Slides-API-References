---
title: set_EmbedImages()
second_title: Aspose.Slides برای مرجع API C++
description: گزینهٔ جاسازی تصاویر را تنظیم می‌کند. مقدار bool را بنویسید.
type: docs
weight: 66
url: /fa/aspose.slides.export/html5options/set_embedimages/
---
## Html5Options::set_EmbedImages(bool) متد

گزینهٔ جاسازی تصویرها را تنظیم می‌کند. مقدار **bool** را بنویسید.

```cpp
void Aspose::Slides::Export::Html5Options::set_EmbedImages(bool value) override
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

* کلاس [Html5Options](../)
* فضای‌نام [Aspose::Slides::Export](../../)
* کتابخانه [Aspose.Slides](../../../)