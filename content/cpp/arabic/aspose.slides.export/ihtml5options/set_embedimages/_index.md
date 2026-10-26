---
title: set_EmbedImages()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يضبط خيار تضمين الصور. اكتب bool.
type: docs
weight: 66
url: /ar/aspose.slides.export/ihtml5options/set_embedimages/
---
## IHtml5Options::set_EmbedImages(bool) طريقة


يضبط خيار تضمين الصور. اكتب **bool**.

```cpp
virtual void Aspose::Slides::Export::IHtml5Options::set_EmbedImages(bool value)=0
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

* الفئة [IHtml5Options](../)
* النطاق [Aspose::Slides::Export](../../)
* المكتبة [Aspose.Slides](../../../)