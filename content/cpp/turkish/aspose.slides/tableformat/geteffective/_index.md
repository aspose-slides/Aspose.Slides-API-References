---
title: GetEffective()
second_title: Aspose.Slides için C++ API Referansı
description: Kalıtım ve tablo stilleri uygulanmış etkili tablo biçimlendirme özelliklerini alır.
type: docs
weight: 40
url: /tr/aspose.slides/tableformat/geteffective/
---
## TableFormat::GetEffective() metodu

Kalıtım ve tablo stilleri uygulanmış etkili tablo biçimlendirme özelliklerini alır.

```cpp
System::SharedPtr<ITableFormatEffectiveData> Aspose::Slides::TableFormat::GetEffective() override
```

### Dönüş Değeri

A [ITableFormatEffectiveData](../../itableformateffectivedata/).

## Açıklamalar

Bu örnek, farklı tablo mantık bölümleri için etkili dolgu biçimini almayı gösterir. Lütfen hücre biçimlendirmesinin her zaman satır biçimlendirmesinden, satırın sütundan, sütunun ise tüm tablodan daha yüksek önceliğe sahip olduğunu unutmayın. Böylece sonunda CellFormatEffectiveData özellikleri tabloyu çizmek için her zaman kullanılır. Aşağıdaki kod sadece bir API örneğidir. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto tbl = AsCast<Table>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto tableFillFormatEffective = tbl->get_TableFormat()->GetEffective()->get_FillFormat();
auto rowFillFormatEffective = tbl->get_Rows()->idx_get(0)->get_RowFormat()->GetEffective()->get_FillFormat();
auto columnFillFormatEffective = tbl->get_Columns()->idx_get(0)->get_ColumnFormat()->GetEffective()->get_FillFormat();
auto cellFillFormatEffective = tbl->idx_get(0, 0)->get_CellFormat()->GetEffective()->get_FillFormat();
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [ITableFormatEffectiveData](../../itableformateffectivedata/)
* Sınıf [TableFormat](../)
* Ad Alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)