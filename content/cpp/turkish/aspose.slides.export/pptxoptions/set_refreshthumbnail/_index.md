---
title: set_RefreshThumbnail()
second_title: Aspose.Slides için C++ API Referansı
description: Sunum küçük resminin yenilenip yenilenmeyeceğini belirtir. bool yazın. Varsayılan değer true.
type: docs
weight: 66
url: /tr/aspose.slides.export/pptxoptions/set_refreshthumbnail/
---
## PptxOptions::set_RefreshThumbnail(bool) yöntemi

Sunum küçük resminin güncellenip güncellenmeyeceğini belirtir. **bool** yazın. Varsayılan değer **true**'dur.

```cpp
void Aspose::Slides::Export::PptxOptions::set_RefreshThumbnail(bool value) override
```

## Açıklamalar

Seçenek değeri **true** olduğunda, yeni küçük resim oluşturulacaktır.

Seçenek değeri **false** olduğunda, mevcut küçük resim olduğu gibi kaydedilir.

Örnek: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_RefreshThumbnail(false);
pres->Save(u"result_with_old_thumbnail.pptx", SaveFormat::Pptx, pptxOptions);
```

## İlgili

* Sınıf [PptxOptions](../)
* Ad alanı [Aspose::Slides::Export](../../)
* Kütüphane [Aspose.Slides](../../../)