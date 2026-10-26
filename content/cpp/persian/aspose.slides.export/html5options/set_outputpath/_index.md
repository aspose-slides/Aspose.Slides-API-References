---
title: set_OutputPath()
second_title: Aspose.Slides برای مرجع API C++
description: "مشخص می‌کند که منابع خارجی باید در کجا ذخیره شوند. System::String را بنویسید."
type: docs
weight: 92
url: /fa/aspose.slides.export/html5options/set_outputpath/
---
## Html5Options::set_OutputPath(System::String) متد


مشخص می‌کند که منابع خارجی باید در کجا ذخیره شوند. [System::String](../../../system/string/) را بنویسید.

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

## همچنین ببینید

* کلاس [String](../../../system/string/)
* کلاس [Html5Options](../)
* فضای‌نام [Aspose::Slides::Export](../../)
* کتابخانه [Aspose.Slides](../../../)