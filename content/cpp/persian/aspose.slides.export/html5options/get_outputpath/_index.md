---
title: get_OutputPath()
second_title: مرجع API Aspose.Slides برای C++
description: "مشخص می‌کند که منابع خارجی در کجا ذخیره شوند. خواندن System::String."
type: docs
weight: 79
url: /fa/aspose.slides.export/html5options/get_outputpath/
---
## Html5Options::get_OutputPath() متد


مشخص می‌کند که منابع خارجی در کجا ذخیره شوند. خواندن [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::Export::Html5Options::get_OutputPath() override
```

## توضیحات


مثال: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<Html5Options> html5Options = System::MakeObject<Html5Options>();
html5Options->set_EmbedImages(true);
html5Options->set_OutputPath(u"the_desired_path");
pres->Save(u"demo-linked-images.html", SaveFormat::Html5, html5Options);
```

## مراجع

* کلاس [String](../../../system/string/)
* کلاس [Html5Options](../)
* فضای‌نام [Aspose::Slides::Export](../../)
* کتابخانه [Aspose.Slides](../../../)