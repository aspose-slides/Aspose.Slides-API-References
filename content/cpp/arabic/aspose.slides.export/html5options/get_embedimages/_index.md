---
title: get_EmbedImages()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يعيد خيار تضمين الصور. قراءة bool.
type: docs
weight: 53
url: /ar/aspose.slides.export/html5options/get_embedimages/
---
## Html5Options::get_EmbedImages() طريقة


يعيد خيار تضمين الصور. قراءة **bool**.

```cpp
bool Aspose::Slides::Export::Html5Options::get_EmbedImages() override
```

## ملاحظات


مثال: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<Html5Options> html5Options = System::MakeObject<Html5Options>();
html5Options->set_EmbedImages(false);
pres->Save(u"demo-linked-images.html", SaveFormat::Html5, html5Options);
```

## انظر أيضًا

* فئة [Html5Options](../)
* نطاق [Aspose::Slides::Export](../../)
* مكتبة [Aspose.Slides](../../../)