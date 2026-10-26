---
title: set_OutputPath()
second_title: Aspose.Slides for C++ API Referansı
description: "Dış kaynakların nerede saklanacağını belirler. System::String yaz."
type: docs
weight: 92
url: /tr/aspose.slides.export/html5options/set_outputpath/
---
## Html5Options::set_OutputPath(System::String) yöntemi

Dış kaynakların nerede saklanacağını belirler. Yaz [System::String](../../../system/string/).

```cpp
void Aspose::Slides::Export::Html5Options::set_OutputPath(System::String value) override
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

## Diğer Bağlantılar

* Sınıf [String](../../../system/string/)
* Sınıf [Html5Options](../)
* AdAlanı [Aspose::Slides::Export](../../)
* Kütüphane [Aspose.Slides](../../../)