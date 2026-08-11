---
title: get_EmbedImages()
second_title: مرجع API Aspose.Slides برای C++
description: گزینهٔ جاسازی تصاویر را برمی‌گرداند. خواند bool.
type: docs
weight: 53
url: /fa/aspose.slides.export/html5options/get_embedimages/
---
## Html5Options::get_EmbedImages() متد

گزینهٔ جاسازی تصاویر را برمی‌گرداند. خواند **bool**.

```cpp
bool Aspose::Slides::Export::Html5Options::get_EmbedImages() override
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
* فضای نام [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)