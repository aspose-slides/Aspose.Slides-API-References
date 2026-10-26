---
title: get_OutputPath()
second_title: Aspose.Slides برای C++ مرجع API
description: "مشخص می‌کند که منابع خارجی در کجا ذخیره شوند. مطالعه کنید System::String."
type: docs
weight: 79
url: /fa/aspose.slides.export/ihtml5options/get_outputpath/
---
## IHtml5Options::get_OutputPath() متد

مشخص می‌کند که منابع خارجی در کجا ذخیره شوند. مطالعه کنید [System::String](../../../system/string/).

```cpp
virtual System::String Aspose::Slides::Export::IHtml5Options::get_OutputPath()=0
```

## توضیحات

مثال: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<Html5Options> html5Options = System::MakeObject<Html5Options>();
html5Options->set_EmbedImages(false);
html5Options->set_OutputPath(u"the_desired_path");
pres->Save(u"demo-linked-images.html", SaveFormat::Html5, html5Options);
```

## موارد مرتبط

* کلاس [String](../../../system/string/)
* کلاس [IHtml5Options](../)
* فضای نام [Aspose::Slides::Export](../../)
* کتابخانه [Aspose.Slides](../../../)