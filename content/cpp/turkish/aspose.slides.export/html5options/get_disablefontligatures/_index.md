---
title: get_DisableFontLigatures()
second_title: Aspose.Slides için C++ API Referansı
description: Metnin ligatürler kullanılmadan render edilip edilmediğini belirten bir değer alır. true olarak ayarlandığında, ligatürler render edilen çıktıda devre dışı bırakılır. Varsayılan olarak, bu özellik false olarak ayarlanmıştır.
type: docs
weight: 131
url: /tr/aspose.slides.export/html5options/get_disablefontligatures/
---
## Html5Options::get_DisableFontLigatures() metodu


Metnin ligatürler kullanılmadan render edilip edilmediğini belirten bir değer alır. **true** olarak ayarlandığında, ligatürler render edilen çıktıda devre dışı bırakılır. Varsayılan olarak, bu özellik **false** olarak ayarlanmıştır.

```cpp
bool Aspose::Slides::Export::Html5Options::get_DisableFontLigatures() override
```

## Açıklamalar


Örnek: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<Html5Options> options = System::MakeObject<Html5Options>();
options->set_DisableFontLigatures(true); // Metin render'ında ligatürleri devre dışı bırak

pres->Save(outputSlidePath, SaveFormat::Html5, options);
```

## İlgili

* Sınıf [Html5Options](../)
* Ad alanı [Aspose::Slides::Export](../../)
* Kütüphane [Aspose.Slides](../../../)