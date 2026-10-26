---
title: set_DefaultRegularFont()
second_title: Aspose.Slides için C++ API Referansı
description: "Kaynak yazı tipi bulunamadığında kullanılan Normal yazı tipini ayarlar. System::String yazın."
type: docs
weight: 40
url: /tr/aspose.slides/loadoptions/set_defaultregularfont/
---
## LoadOptions::set_DefaultRegularFont(System::String) metod

Kaynak yazı tipi bulunamadığında kullanılan Normal yazı tipini ayarlar. Yazın [System::String](../../../system/string/).

```cpp
void Aspose::Slides::LoadOptions::set_DefaultRegularFont(System::String value) override
```

## Açıklamalar

Aşağıdaki örnek, PowerPoint [Presentation](../../presentation/) oluşturulması için varsayılan yazı tiplerinin nasıl ayarlanacağını gösterir.

```cpp
// Yükleme seçeneklerini kullanarak varsayılan normal ve Asya yazı tiplerini tanımlayın
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>(LoadFormat::Auto);
loadOptions->set_DefaultRegularFont(u"Wingdings");
loadOptions->set_DefaultAsianFont(u"Wingdings");

// Sunumu yükle
auto pptx = System::MakeObject<Presentation>(u"DefaultFonts.pptx", loadOptions);
// Slayt küçük resmi üret
auto slide = pptx->get_Slides()->idx_get(0);
slide->GetThumbnail(1.0f, 1.0f)->Save(u"output_out.png", System::Drawing::Imaging::ImageFormat::get_Png());

// PDF oluştur
pptx->Save(u"output_out.pdf", SaveFormat::Pdf);
// XPS oluştur
pptx->Save(u"output_out.xps", SaveFormat::Xps);
```

## Diğer Bağlantılar

* Sınıf [String](../../../system/string/)
* Sınıf [LoadOptions](../)
* Ad Alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)