---
title: get_DefaultRegularFont()
second_title: Aspose.Slides for C++ API Referansı
description: "Kaynak yazı tipi bulunamadığında kullanılan Normal yazı tipini döndürür. System::String'i okuyun."
type: docs
weight: 27
url: /tr/aspose.slides/loadoptions/get_defaultregularfont/
---
## LoadOptions::get_DefaultRegularFont() metodu


Kaynak yazı tipi bulunamadığında kullanılan Normal yazı tipini döndürür. Okuyun [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::LoadOptions::get_DefaultRegularFont() override
```

## Açıklamalar


Aşağıdaki örnek, PowerPoint [Presentation](../../presentation/) görüntülenmesi için varsayılan yazı tiplerini nasıl ayarlayacağını gösterir. 
```cpp
// Yükleme seçeneklerini kullanarak varsayılan normal ve Asya yazı tiplerini tanımlayın
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>(LoadFormat::Auto);
loadOptions->set_DefaultRegularFont(u"Wingdings");
loadOptions->set_DefaultAsianFont(u"Wingdings");

// Sunumu yükle
auto pptx = System::MakeObject<Presentation>(u"DefaultFonts.pptx", loadOptions);
// Slayt küçük resmi oluştur
auto slide = pptx->get_Slides()->idx_get(0);
slide->GetThumbnail(1.0f, 1.0f)->Save(u"output_out.png", System::Drawing::Imaging::ImageFormat::get_Png());

// PDF oluştur
pptx->Save(u"output_out.pdf", SaveFormat::Pdf);
// XPS oluştur
pptx->Save(u"output_out.xps", SaveFormat::Xps);
```

## Ayrıca Bakınız

* Sınıf [String](../../../system/string/)
* Sınıf [LoadOptions](../)
* İsim Alanı [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)