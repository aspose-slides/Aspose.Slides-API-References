---
title: set_OutputPath()
second_title: Aspose.Slides برای C++ مرجع API
description: "تعیین می‌کند که منابع خارجی در کجا ذخیره شوند. بنویسید System::String."
type: docs
weight: 92
url: /fa/aspose.slides.export/ihtml5options/set_outputpath/
---
## IHtml5Options::set_OutputPath(System::String) متد


تعیین می‌کند که منابع خارجی در کجا ذخیره شوند. بنویسید [System::String](../../../system/string/).

```cpp
virtual void Aspose::Slides::Export::IHtml5Options::set_OutputPath(System::String value)=0
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
* فضای‌نام [Aspose::Slides::Export](../../)
* کتابخانه [Aspose.Slides](../../../)