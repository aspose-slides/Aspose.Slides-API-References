---
title: get_OutputPath()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "يحدد أين يجب تخزين الموارد الخارجية. اقرأ System::String."
type: docs
weight: 79
url: /ar/aspose.slides.export/html5options/get_outputpath/
---
## Html5Options::get_OutputPath() الطريقة

يحدد أين يجب تخزين الموارد الخارجية. اقرأ [System::String](../../../system/string/).

```cpp
System::String Aspense::Slides::Export::Html5Options::get_OutputPath() override
```

## الملاحظات

مثال:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<Html5Options> html5Options = System::MakeObject<Html5Options>();
html5Options->set_EmbedImages(true);
html5Options->set_OutputPath(u"the_desired_path");
pres->Save(u"demo-linked-images.html", SaveFormat::Html5, html5Options);
```

## انظر أيضًا

* الفئة [String](../../../system/string/)
* الفئة [Html5Options](../)
* النطاق [Aspose::Slides::Export](../../)
* المكتبة [Aspose.Slides](../../../)