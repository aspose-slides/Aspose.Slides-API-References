---
title: set_RefreshThumbnail()
second_title: Aspose.Slides for C++ API Referansı
description: Sunum küçük resminin yenilenip yenilenmeyeceğini belirtir. bool yazın. Varsayılan değer true.
type: docs
weight: 66
url: /tr/aspose.slides.export/ipptxoptions/set_refreshthumbnail/
---
## IPptxOptions::set_RefreshThumbnail(bool) method

Sunum küçük resminin yenilenip yenilenmeyeceğini belirtir. **bool** yazın. Varsayılan değer **true**'dir.

```cpp
virtual void Aspose::Slides::Export::IPptxOptions::set_RefreshThumbnail(bool value)=0
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

## Diğer Bilgiler

* Sınıf [IPptxOptions](../)
* Ad Alanı [Aspose::Slides::Export](../../)
* Kütüphane [Aspose.Slides](../../../)