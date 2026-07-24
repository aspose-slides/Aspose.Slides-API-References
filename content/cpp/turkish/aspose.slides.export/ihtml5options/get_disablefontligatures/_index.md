---
title: get_DisableFontLigatures()
second_title: Aspose.Slides for C++ API Referansı
description: Metnin bağlamlar kullanılmadan işlenip işlenmediğini gösteren bir değer alır. true olarak ayarlandığında, bağlamlar oluşturulan çıktıda devre dışı bırakılır. Varsayılan olarak, bu özellik false olarak ayarlanır.
type: docs
weight: 131
url: /tr/aspose.slides.export/ihtml5options/get_disablefontligatures/
---
## IHtml5Options::get_DisableFontLigatures() method


Metnin bağlamlar kullanılmadan işlenip işlenmediğini gösteren bir değer alır. **true** olarak ayarlandığında, bağlamlar oluşturulan çıktıda devre dışı bırakılır. Varsayılan olarak, bu özelliğin değeri **false** olarak ayarlanmıştır.

```cpp
virtual bool Aspose::Slides::Export::IHtml5Options::get_DisableFontLigatures()=0
```

## Açıklamalar


Örnek: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<Html5Options> options = System::MakeObject<Html5Options>();
options->set_DisableFontLigatures(true); // Metin işleme sırasında bağlamaları devre dışı bırak

pres->Save(outputSlidePath, SaveFormat::Html5, options);
```

## Ayrıca Bakınız

* Sınıf [IHtml5Options](../)
* Ad Alanı [Aspose::Slides::Export](../../)
* Kütüphane [Aspose.Slides](../../../)