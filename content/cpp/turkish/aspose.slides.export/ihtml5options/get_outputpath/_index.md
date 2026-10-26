---
title: get_OutputPath()
second_title: Aspose.Slides için C++ API Referansı
description: "Harici kaynakların nerede saklanacağını belirler. System::String'i okuyun."
type: docs
weight: 79
url: /tr/aspose.slides.export/ihtml5options/get_outputpath/
---
## IHtml5Options::get_OutputPath() metodu


Harici kaynakların nerede saklanacağını belirler. [System::String](../../../system/string/) belgelerine bakınız.

```cpp
virtual System::String Aspose::Slides::Export::IHtml5Options::get_OutputPath()=0
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

## Diğer Sayfalara Bak

* Sınıf [String](../../../system/string/)
* Sınıf [IHtml5Options](../)
* Ad Alanı [Aspose::Slides::Export](../../)
* Kütüphane [Aspose.Slides](../../../)