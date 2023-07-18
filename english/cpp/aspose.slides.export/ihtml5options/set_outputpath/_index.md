---
title: set_OutputPath()
second_title: Aspose.Slides for C++ API Reference
description: "Determines where external resources should be stored. Write System::String."
type: docs
weight: 92
url: /cpp/aspose.slides.export/ihtml5options/set_outputpath/
---
## IHtml5Options::set_OutputPath(System::String) method


Determines where external resources should be stored. Write [System::String](../../../system/string/).

```cpp
virtual void Aspose::Slides::Export::IHtml5Options::set_OutputPath(System::String value)=0
```

## Remarks


Example: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<Html5Options> html5Options = System::MakeObject<Html5Options>();
html5Options->set_EmbedImages(false);
html5Options->set_OutputPath(u"the_desired_path");
pres->Save(u"demo-linked-images.html", SaveFormat::Html5, html5Options);
```

## See Also

* Class [String](../../../system/string/)
* Class [IHtml5Options](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)