---
title: set_OutputPath()
second_title: مرجع API Aspose.Slides للغة C++
description: "يحدد مكان تخزين الموارد الخارجية. اكتب System::String."
type: docs
weight: 92
url: /ar/aspose.slides.export/ihtml5options/set_outputpath/
---
## IHtml5Options::set_OutputPath(System::String) طريقة

يحدد مكان تخزين الموارد الخارجية. اكتب [System::String](../../../system/string/).

```cpp
virtual void Aspose::Slides::Export::IHtml5Options::set_OutputPath(System::String value)=0
```

## ملاحظات

مثال:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<Html5Options> html5Options = System::MakeObject<Html5Options>();
html5Options->set_EmbedImages(false);
html5Options->set_OutputPath(u"the_desired_path");
pres->Save(u"demo-linked-images.html", SaveFormat::Html5, html5Options);
```

## راجع أيضًا

* فئة [String](../../../system/string/)
* فئة [IHtml5Options](../)
* مساحة الاسم [Aspose::Slides::Export](../../)
* مكتبة [Aspose.Slides](../../../)