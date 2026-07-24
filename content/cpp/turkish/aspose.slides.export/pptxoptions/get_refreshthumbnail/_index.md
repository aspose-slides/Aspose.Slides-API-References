---
title: get_RefreshThumbnail()
second_title: Aspose.Slides for C++ API Referansı
description: Sunum thumbnail'ının yenilenip yenilenmeyeceğini belirtir. Okunur bool. Varsayılan değer true.
type: docs
weight: 53
url: /tr/aspose.slides.export/pptxoptions/get_refreshthumbnail/
---
## PptxOptions::get_RefreshThumbnail() metodu


Sunum thumbnail'ının yenilenip yenilenmeyeceğini belirtir. Okunur **bool**. Varsayılan değer **true**.

```cpp
bool Aspose::Slides::Export::PptxOptions::get_RefreshThumbnail() override
```

## Açıklamalar


Seçenek değeri **true** olduğunda, yeni thumbnail oluşturulur.

Seçenek değeri **false** olduğunda, mevcut thumbnail olduğu gibi kaydedilir.

Örnek: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_RefreshThumbnail(false);
pres->Save(u"result_with_old_thumbnail.pptx", SaveFormat::Pptx, pptxOptions);
```

## Ayrıca Bakınız

* Sınıf [PptxOptions](../)
* İsim Alanı [Aspose::Slides::Export](../../)
* Kütüphane [Aspose.Slides](../../../)