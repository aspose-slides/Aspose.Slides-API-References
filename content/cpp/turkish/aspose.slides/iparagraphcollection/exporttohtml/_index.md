---
title: ExportToHtml()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen paragrafları HTML'ye dönüştürür ve String nesnesi olarak döndürür.
type: docs
weight: 105
url: /tr/aspose.slides/iparagraphcollection/exporttohtml/
---
## IParagraphCollection::ExportToHtml(int32_t, int32_t, System::SharedPtr\<Export::ITextToHtmlConversionOptions\>) method

Belirtilen paragrafları HTML'ye dönüştürür ve String nesnesi olarak döndürür.

```cpp
virtual System::String Aspose::Slides::IParagraphCollection::ExportToHtml(int32_t firstParagraphIndex, int32_t paragraphsCount, System::SharedPtr<Export::ITextToHtmlConversionOptions> options)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| firstParagraphIndex | **int32_t** | İlk paragraf indeksi **int32_t** |
| paragraphsCount | **int32_t** | [Paragraph](../../paragraph/) sayısı **int32_t** |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ITextToHtmlConversionOptions](../../../aspose.slides.export/itexttohtmlconversionoptions/)\> | Dönüştürme seçenekleri [Export::ITextToHtmlConversionOptions](../../../aspose.slides.export/itexttohtmlconversionoptions/) |

### Dönüş Değeri

Oluşturulan HTML.

## Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [String](../../../system/string/)
* Sınıf [ITextToHtmlConversionOptions](../../../aspose.slides.export/itexttohtmlconversionoptions/)
* Sınıf [IParagraphCollection](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)