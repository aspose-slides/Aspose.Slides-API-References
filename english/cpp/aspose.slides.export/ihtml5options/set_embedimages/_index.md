---
title: set_EmbedImages()
second_title: Aspose.Slides for C++ API Reference
description: Sets images embedding option. Write bool.
type: docs
weight: 66
url: /cpp/aspose.slides.export/ihtml5options/set_embedimages/
---
## IHtml5Options::set_EmbedImages(bool) method


Sets images embedding option. Write **bool**.

```cpp
virtual void Aspose::Slides::Export::IHtml5Options::set_EmbedImages(bool value)=0
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

* Class [IHtml5Options](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)