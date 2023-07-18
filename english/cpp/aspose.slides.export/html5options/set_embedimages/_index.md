---
title: set_EmbedImages()
second_title: Aspose.Slides for C++ API Reference
description: Sets images embedding option. Write bool.
type: docs
weight: 66
url: /cpp/aspose.slides.export/html5options/set_embedimages/
---
## Html5Options::set_EmbedImages(bool) method


Sets images embedding option. Write **bool**.

```cpp
void Aspose::Slides::Export::Html5Options::set_EmbedImages(bool value) override
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