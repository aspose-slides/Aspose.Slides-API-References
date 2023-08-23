---
title: get_EmbedImages()
second_title: Aspose.Slides for C++ API Reference
description: Returns images embedding option. Read bool.
type: docs
weight: 53
url: /aspose.slides.export/html5options/get_embedimages/
---
## Html5Options::get_EmbedImages() method


Returns images embedding option. Read **bool**.

```cpp
bool Aspose::Slides::Export::Html5Options::get_EmbedImages() override
```

## Remarks


Example: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<Html5Options> html5Options = System::MakeObject<Html5Options>();
html5Options->set_EmbedImages(false);
pres->Save(u"demo-linked-images.html", SaveFormat::Html5, html5Options);
```

## See Also

* Class [Html5Options](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)