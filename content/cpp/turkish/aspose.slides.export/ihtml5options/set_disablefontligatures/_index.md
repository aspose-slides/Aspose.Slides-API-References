---
title: set_DisableFontLigatures()
second_title: Aspose.Slides C++ API Referansı
description: Metnin ligatürler kullanılmadan render edilip edilmediğini belirten bir değer atar. true olarak ayarlandığında, ligatürler render edilen çıktıda devre dışı bırakılır. Varsayılan olarak, bu özellik false olarak ayarlanır.
type: docs
weight: 144
url: /tr/aspose.slides.export/ihtml5options/set_disablefontligatures/
---
## IHtml5Options::set_DisableFontLigatures(bool) metod


Metin, ligatürler kullanılmadan render edilip edilmeyeceğini belirten bir değer atar. **true** olarak ayarlandığında, ligatürler render edilmiş çıktıda devre dışı bırakılır. Varsayılan olarak, bu özellik **false** olarak ayarlanmıştır.

```cpp
virtual void Aspose::Slides::Export::IHtml5Options::set_DisableFontLigatures(bool value)=0
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

* Sınıf [IHtml5Options](../)
* AdAlanı [Aspose::Slides::Export](../../)
* Kütüphane [Aspose.Slides](../../../)