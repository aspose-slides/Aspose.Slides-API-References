---
title: get_RefreshThumbnail()
second_title: Aspose.Slides için C++ API Referansı
description: Sunum küçük resminin yenilenip yenilenmeyeceğini belirtir. Okunur bool. Varsayılan değer true.
type: docs
weight: 53
url: /tr/aspose.slides.export/ipptxoptions/get_refreshthumbnail/
---
## IPptxOptions::get_RefreshThumbnail() metod


Sunum küçük resminin yenilenip yenilenmeyeceğini belirtir. Okunur **bool**. Varsayılan değer **true**.

```cpp
virtual bool Aspose::Slides::Export::IPptxOptions::get_RefreshThumbnail()=0
```

## Açıklamalar


Seçenek değeri **true** olduğunda, yeni küçük resim oluşturulacaktır.

Seçenek değeri **false** olduğunda, mevcut küçük resim olduğu gibi kaydedilecektir.

Örnek: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_RefreshThumbnail(false);
pres->Save(u"result_with_old_thumbnail.pptx", SaveFormat::Pptx, pptxOptions);
```

## Ayrıca Bakınız

* Sınıf [IPptxOptions](../)
* İsim Alanı [Aspose::Slides::Export](../../)
* Kütüphane [Aspose.Slides](../../../)