---
title: get_OutputPath()
second_title: Aspose.Slides for C++ API Reference
description: "Determines where external resources should be stored. Read System::String."
type: docs
weight: 79
url: /aspose.slides.export/html5options/get_outputpath/
---
## Html5Options::get_OutputPath() method


Determines where external resources should be stored. Read [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::Export::Html5Options::get_OutputPath() override
```

## Remarks


Example: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<Html5Options> html5Options = System::MakeObject<Html5Options>();
html5Options->set_EmbedImages(true);
html5Options->set_OutputPath(u"the_desired_path");
pres->Save(u"demo-linked-images.html", SaveFormat::Html5, html5Options);
```

## See Also

* Class [String](../../../system/string/)
* Class [Html5Options](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)