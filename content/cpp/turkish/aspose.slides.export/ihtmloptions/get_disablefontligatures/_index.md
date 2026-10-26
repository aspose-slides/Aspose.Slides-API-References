---
title: get_DisableFontLigatures()
second_title: C++ için Aspose.Slides API Referansı
description: Metnin ligaturler kullanılmadan render edilip edilmediğini gösteren bir değer alır. true olarak ayarlandığında, ligaturler oluşturulan çıktıda devre dışı bırakılır. Varsayılan olarak, bu özellik false olarak ayarlanmıştır.
type: docs
weight: 183
url: /tr/aspose.slides.export/ihtmloptions/get_disablefontligatures/
---
## IHtmlOptions::get_DisableFontLigatures() metodu


Metnin ligaturler kullanılmadan çizilip çizilmediğini gösteren bir değer alır. **true** olarak ayarlandığında, ligaturler oluşturulan çıktıda devre dışı bırakılır. Varsayılan olarak, bu özellik **false** olarak ayarlanmıştır.

```cpp
virtual bool Aspose::Slides::Export::IHtmlOptions::get_DisableFontLigatures()=0
```

## Açıklamalar


Örnek: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_DisableFontLigatures(true); // Metin render'ında ligaturleri devre dışı bırak

pres->Save(outputSlidePath, SaveFormat::Html, options);
```

## Ayrıca Bakınız

* Sınıf [IHtmlOptions](../)
* Ad alanı [Aspose::Slides::Export](../../)
* Kütüphane [Aspose.Slides](../../../)