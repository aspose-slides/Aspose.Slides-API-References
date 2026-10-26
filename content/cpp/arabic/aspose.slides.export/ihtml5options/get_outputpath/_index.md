---
title: get_OutputPath()
second_title: Aspose.Slides للغة C++ مرجع API
description: "يحدد أين يجب تخزين الموارد الخارجية. اقرأ System::String."
type: docs
weight: 79
url: /ar/aspose.slides.export/ihtml5options/get_outputpath/
---
## IHtml5Options::get_OutputPath() طريقة

يحدد أين يجب تخزين الموارد الخارجية. اقرأ [System::String](../../../system/string/).

```cpp
virtual System::String Aspose::Slides::Export::IHtml5Options::get_OutputPath()=0
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

## انظر أيضًا

* فئة [String](../../../system/string/)
* فئة [IHtml5Options](../)
* نطاق [Aspose::Slides::Export](../../)
* مكتبة [Aspose.Slides](../../../)