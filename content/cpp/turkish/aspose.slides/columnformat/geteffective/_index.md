---
title: GetEffective()
second_title: Aspose.Slides için C++ API Referansı
description: Miras ve tablo stilleri uygulanmış etkili tablo sütun biçimlendirme özelliklerini alır.
type: docs
weight: 1
url: /tr/aspose.slides/columnformat/geteffective/
---
## ColumnFormat::GetEffective() metod


Miras ve tablo stilleri uygulanmış etkili tablo sütun biçimlendirme özelliklerini alır.

```cpp
System::SharedPtr<IColumnFormatEffectiveData> Aspose::Slides::ColumnFormat::GetEffective() override
```


### Dönüş Değeri

Bir [IColumnFormatEffectiveData](../../icolumnformateffectivedata/).
## Açıklamalar



Bu örnek, farklı tablo mantık bölümleri için etkili dolgu biçimini almayı gösterir. Lütfen hücre biçimlemesinin her zaman satır biçimlemesinden daha yüksek önceliğe, satırın sütundan, sütunun da tüm tablodan daha yüksek önceliğe sahip olduğunu unutmayın. Bu nedenle CellFormatEffectiveData özellikleri tabloyu çizerken her zaman kullanılır. Aşağıdaki kod sadece bir API örneğidir. 
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
* Sınıf [IColumnFormatEffectiveData](../../icolumnformateffectivedata/)
* Sınıf [ColumnFormat](../)
* AdAlanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)