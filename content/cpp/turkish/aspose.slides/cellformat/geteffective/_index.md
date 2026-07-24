---
title: GetEffective()
second_title: Aspose.Slides for C++ API Referansı
description: Kalıtım ve tablo stilleri uygulanmış etkili tablo hücresi biçimlendirme özelliklerini alır.
type: docs
weight: 118
url: /tr/aspose.slides/cellformat/geteffective/
---
## CellFormat::GetEffective() metodu

Kalıtım ve tablo stilleri uygulanmış etkili tablo hücresi biçimlendirme özelliklerini alır.

```cpp
System::SharedPtr<ICellFormatEffectiveData> Aspose::Slides::CellFormat::GetEffective() override
```

### Dönüş Değeri

Bir [ICellFormatEffectiveData](../../icellformateffectivedata/).

## Açıklamalar

Bu örnek, farklı tablo mantık bölümleri için etkili dolgu biçimini almayı gösterir. Lütfen hücre biçimlendirmesinin her zaman satır biçimlendirmesinden daha yüksek önceliğe sahip olduğunu, satırın sütundan, sütunun ise bütün tablodan daha yüksek olduğunu unutmayın. Bu nedenle sonunda CellFormatEffectiveData özellikleri her zaman tabloyu çizerken kullanılır. Aşağıdaki kod sadece bir API örneğidir. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto tbl = AsCast<Table>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto tableFillFormatEffective = tbl->get_TableFormat()->GetEffective()->get_FillFormat();
auto rowFillFormatEffective = tbl->get_Rows()->idx_get(0)->get_RowFormat()->GetEffective()->get_FillFormat();
auto columnFillFormatEffective = tbl->get_Columns()->idx_get(0)->get_ColumnFormat()->GetEffective()->get_FillFormat();
auto cellFillFormatEffective = tbl->idx_get(0, 0)->get_CellFormat()->GetEffective()->get_FillFormat();
// Çıktı ve karşılaştırma
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [ICellFormatEffectiveData](../../icellformateffectivedata/)
* Sınıf [CellFormat](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)