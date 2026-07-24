---
title: set_OutputPath()
second_title: Aspose.Slides için C++ API Referansı
description: "Harici kaynakların nerede saklanacağını belirler. System::String yazın."
type: docs
weight: 92
url: /tr/aspose.slides.export/ihtml5options/set_outputpath/
---
## IHtml5Options::set_OutputPath(System::String) yöntemi


Harici kaynakların nerede saklanacağını belirler. [System::String](../../../system/string/) yazın.

```cpp
virtual void Aspose::Slides::Export::IHtml5Options::set_OutputPath(System::String value)=0
```

## Açıklamalar


Örnek: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<Html5Options> html5Options = System::MakeObject<Html5Options>();
html5Options->set_EmbedImages(false);
html5Options->set_OutputPath(u"the_desired_path");
pres->Save(u"demo-linked-images.html", SaveFormat::Html5, html5Options);
```

## Ayrıca Bakınız

* Sınıf [String](../../../system/string/)
* Sınıf [IHtml5Options](../)
* Ad alanı [Aspose::Slides::Export](../../)
* Kütüphane [Aspose.Slides](../../../)