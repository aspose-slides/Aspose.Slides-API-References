---
title: get_OutputPath()
second_title: Aspose.Slides için C++ API Referansı
description: "Dış kaynakların nereye depolanması gerektiğini belirler. System::String okuyun."
type: docs
weight: 79
url: /tr/aspose.slides.export/html5options/get_outputpath/
---
## Html5Options::get_OutputPath() metodu


Dış kaynakların nerede depolanması gerektiğini belirler. Okuyun [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::Export::Html5Options::get_OutputPath() override
```

## Açıklamalar


Örnek: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<Html5Options> html5Options = System::MakeObject<Html5Options>();
html5Options->set_EmbedImages(true);
html5Options->set_OutputPath(u"the_desired_path");
pres->Save(u"demo-linked-images.html", SaveFormat::Html5, html5Options);
```

## Ayrıca Bakınız

* Sınıf [String](../../../system/string/)
* Sınıf [Html5Options](../)
* İsim Alanı [Aspose::Slides::Export](../../)
* Kütüphane [Aspose.Slides](../../../)