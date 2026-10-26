---
title: set_EmbedImages()
second_title: Aspose.Slides لمرجع API للغة C++
description: يضبط خيار تضمين الصور. اكتب bool.
type: docs
weight: 66
url: /ar/aspose.slides.export/html5options/set_embedimages/
---
## Html5Options::set_EmbedImages(bool) طريقة

يضبط خيار تضمين الصور. اكتب **bool**.

```cpp
void Aspose::Slides::Export::Html5Options::set_EmbedImages(bool value) override
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

* الفئة [Html5Options](../)
* المساحة الاسمية [Aspose::Slides::Export](../../)
* المكتبة [Aspose.Slides](../../../)