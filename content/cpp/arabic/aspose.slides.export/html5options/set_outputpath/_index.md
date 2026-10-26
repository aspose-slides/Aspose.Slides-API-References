---
title: set_OutputPath()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "يحدد أين يجب تخزين الموارد الخارجية. اكتب System::String."
type: docs
weight: 92
url: /ar/aspose.slides.export/html5options/set_outputpath/
---
## Html5Options::set_OutputPath(System::String) طريقة

يحدد أين يجب تخزين الموارد الخارجية. اكتب [System::String](../../../system/string/).

```cpp
void Aspose::Slides::Export::Html5Options::set_OutputPath(System::String value) override
```

## ملاحظات

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