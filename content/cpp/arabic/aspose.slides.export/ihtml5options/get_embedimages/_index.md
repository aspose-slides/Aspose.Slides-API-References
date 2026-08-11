---
title: get_EmbedImages()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يعيد خيار تضمين الصور. قراءة bool.
type: docs
weight: 53
url: /ar/aspose.slides.export/ihtml5options/get_embedimages/
---
## IHtml5Options::get_EmbedImages() طريقة

يعيد خيار تضمين الصور. قراءة **bool**.

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

## أنظر أيضًا

* الفئة [IHtml5Options](../)
* النطاق [Aspose::Slides::Export](../../)
* المكتبة [Aspose.Slides](../../../)